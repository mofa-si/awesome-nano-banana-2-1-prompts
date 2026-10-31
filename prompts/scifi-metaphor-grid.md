# Four Science-Fiction Movies as Editorial Metaphors

[![Preview](https://bibigpt-apps.chatvid.ai/awesome/nano-banana-2-1/2116149873053520259-card.webp)](https://chatimg.ai/prompts/nano-banana-2-1/scifi-metaphor-grid?utm_source=github&utm_medium=readme&utm_campaign=awesome-nano-banana-2-1-prompts&utm_content=scifi-metaphor-grid)

**[▶ Use this prompt on ChatImg](https://chatimg.ai/image?model=nanobanana-2.1&q=2x2+grid%2C+16%3A9%2C+do+this+for+4+famous+scifi+movies%3A+class+UniversalEditorialMetaphor%3A%0A%0A++++def+__init__%28self%2C+topic%29%3A%0A++++++++self.topic+%3D+topic%0A%0A++++++++self.semantics+%3D+infer_semantic_structure%28topic%29%0A++++++++self.thesis+%3D+infer_visual_thesis%28topic%29%0A++++++++self.mood+%3D+infer_editorial_tone%28topic%29%0A%0A++++++++self.metaphors+%3D+generate_candidate_metaphors%28%0A++++++++++++topic%2C%0A++++++++++++count%3D12%0A++++++++%29%0A%0A++++++++self.+best_metaphor+%3D+self.+select_best_metaphor%28%29%0A%0A++++def+select_best_metaphor%28self%29%3A%0A++++++++return+max%28%0A++++++++++++self.metaphors%2C%0A++++++++++++key%3Dlambda+m%3A%0A++++++++++++++++0.35+*+semantic_accuracy%28m%29%0A++++++++++++++%2B+0.25+*+conceptual_originality%28m%29%0A++++++++++++++%2B+0.25+*+visual_clarity%28m%29%0A++++++++++++++%2B+0.15+*+silhouette_strength%28m%29%0A++++++++%29%0A%0A++++def+visual_actors%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22primary%22%3A+infer_dominant_form%28%0A++++++++++++++++self.+best_metaphor%0A++++++++++++%29%2C%0A++++++++++++%22secondary%22%3A+infer_consequence_or_partner%28%0A++++++++++++++++self.+best_metaphor%0A++++++++++++%29%2C%0A++++++++++++%22interaction%22%3A+infer_decisive_action%28%0A++++++++++++++++self.+best_metaphor%0A++++++++++++%29%0A++++++++%7D%0A%0A++++def+composition%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22geometry%22%3A+%22asymmetric%22%2C%0A++++++++++++%22primary_scale%22%3A+%22monumental%22%2C%0A++++++++++++%22secondary_scale%22%3A+%22small%22%2C%0A++++++++++++%22camera%22%3A+%22flat+editorial+orthographic%22%2C%0A++++++++++++%22cropping%22%3A+%22dramatic+boundary+intrusion%22%2C%0A++++++++++++%22negative_space%22%3A+%22dominant%22%2C%0A++++++++++++%22focal_point%22%3A+%22physical+interaction%22%0A++++++++%7D%0A%0A++++def+typography%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22heading%22%3A+derive_chapter_title%28self.topic%29%2C%0A++++++++++++%22embedded_word%22%3A+infer_single_action_label_if_needed%28%0A++++++++++++++++self.topic%0A++++++++++++%29%2C%0A++++++++++++%22density%22%3A+%22minimal%22%0A++++++++%7D%0A%0A++++def+render_style%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22background%22%3A+%22warm+ivory%22%2C%0A++++++++++++%22foreground%22%3A+%22near-black%22%2C%0A++++++++++++%22interior_lines%22%3A+%22fine+white+contours%22%2C%0A++++++++++++%22shadows%22%3A+None%2C%0A++++++++++++%22gradients%22%3A+None%2C%0A++++++++++++%22texture%22%3A+%22minimal+editorial+print%22%2C%0A++++++++++++%22format%22%3A+%22wide+conceptual+illustration%22%0A++++++++%7D%0A%0A++++def+render%28self%29%3A%0A++++++++return+compose%28%0A++++++++++++actors%3Dself.visual_actors%28%29%2C%0A++++++++++++metaphor%3Dself.+best_metaphor%2C%0A++++++++++++layout%3Dself.composition%28%29%2C%0A++++++++++++typography%3Dself.typography%28%29%2C%0A++++++++++++style%3Dself.render_style%28%29%0A++++++++%29%0A%0AFINAL_IMAGE+%3D+UniversalEditorialMetaphor%28%0A++++topic%3D%22%5BTOPIC%5D%22%0A%29.render%28%29&utm_source=github&utm_medium=readme&utm_campaign=awesome-nano-banana-2-1-prompts&utm_content=scifi-metaphor-grid)** · [Source post](https://x.com/Gdgtify/status/2116149873053520259)

- Author / credit: Gadgetify (@Gdgtify)
- Prompt status: `verbatim`

## Prompt

```text
2x2 grid, 16:9, do this for 4 famous scifi movies: class UniversalEditorialMetaphor:

    def __init__(self, topic):
        self.topic = topic

        self.semantics = infer_semantic_structure(topic)
        self.thesis = infer_visual_thesis(topic)
        self.mood = infer_editorial_tone(topic)

        self.metaphors = generate_candidate_metaphors(
            topic,
            count=12
        )

        self. best_metaphor = self. select_best_metaphor()

    def select_best_metaphor(self):
        return max(
            self.metaphors,
            key=lambda m:
                0.35 * semantic_accuracy(m)
              + 0.25 * conceptual_originality(m)
              + 0.25 * visual_clarity(m)
              + 0.15 * silhouette_strength(m)
        )

    def visual_actors(self):
        return {
            "primary": infer_dominant_form(
                self. best_metaphor
            ),
            "secondary": infer_consequence_or_partner(
                self. best_metaphor
            ),
            "interaction": infer_decisive_action(
                self. best_metaphor
            )
        }

    def composition(self):
        return {
            "geometry": "asymmetric",
            "primary_scale": "monumental",
            "secondary_scale": "small",
            "camera": "flat editorial orthographic",
            "cropping": "dramatic boundary intrusion",
            "negative_space": "dominant",
            "focal_point": "physical interaction"
        }

    def typography(self):
        return {
            "heading": derive_chapter_title(self.topic),
            "embedded_word": infer_single_action_label_if_needed(
                self.topic
            ),
            "density": "minimal"
        }

    def render_style(self):
        return {
            "background": "warm ivory",
            "foreground": "near-black",
            "interior_lines": "fine white contours",
            "shadows": None,
            "gradients": None,
            "texture": "minimal editorial print",
            "format": "wide conceptual illustration"
        }

    def render(self):
        return compose(
            actors=self.visual_actors(),
            metaphor=self. best_metaphor,
            layout=self.composition(),
            typography=self.typography(),
            style=self.render_style()
        )

FINAL_IMAGE = UniversalEditorialMetaphor(
    topic="[TOPIC]"
).render()
```

Prompt source: https://x.com/Gdgtify/status/2116149873053520259

## Sources & attribution

- [Gadgetify](https://x.com/Gdgtify) — [source post](https://x.com/Gdgtify/status/2116149873053520259)

Original media, prompts and post text remain the property of their creators. See [media rights](../MEDIA-RIGHTS.md).

[More Nano Banana 2.1 work on ChatImg →](https://chatimg.ai/prompts/nano-banana-2-1?utm_source=github&utm_medium=readme&utm_campaign=awesome-nano-banana-2-1-prompts)
