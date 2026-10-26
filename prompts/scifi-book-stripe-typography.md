# Sci-Fi Books in Optical Stripe Typography

[![Preview](https://bibigpt-apps.chatvid.ai/awesome/nano-banana-2-1/2109182713802707328-card.webp)](https://chatimg.ai/prompts/nano-banana-2-1/scifi-book-stripe-typography?utm_source=github&utm_medium=readme&utm_campaign=awesome-nano-banana-2-1-prompts&utm_content=scifi-book-stripe-typography)

**[▶ Use this prompt on ChatImg](https://chatimg.ai/image?model=nanobanana-2.1&q=2x2+grid%2C+16%3A9%2C+do+this+for+4+famous+scifi+books++class+OpticalStripeTypographicSilhouette%3A%0A++++def+__init__%28self%2C+topic%29%3A%0A++++++++self.topic+%3D+topic%0A++++++++self.word+%3D+derive_short_display_word%28topic%29%0A++++++++self.silhouette+%3D+infer_iconic_silhouette%28topic%29%0A%0A++++++++self.stripe_map+%3D+infer_contour_stripe_paths%28topic%2C+self.silhouette%29%0A++++++++self.typography+%3D+integrate_word_into_body%28self.word%2C+self.silhouette%29%0A++++++++self.negative_space+%3D+solve_white_space_for_readability%28topic%29%0A%0A++++def+silhouette_system%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22subject%22%3A+self.silhouette%2C%0A++++++++++++%22style%22%3A+%22flat+black-and-white+vector+silhouette%22%2C%0A++++++++++++%22recognition%22%3A+%22instant+at+thumbnail+scale%22%0A++++++++%7D%0A%0A++++def+stripe_system%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22paths%22%3A+self.stripe_map%2C%0A++++++++++++%22behavior%22%3A+%22flowing+contour+bands+that+describe+form%22%2C%0A++++++++++++%22palette%22%3A+%22black+stripes+on+white+ground%22%2C%0A++++++++++++%22texture%22%3A+%22none%2C+pure+graphic+ink%22%0A++++++++%7D%0A%0A++++def+word_system%28self%29%3A%0A++++++++return+%7B%0A++++++++++++%22text%22%3A+self.word%2C%0A++++++++++++%22integration%22%3A+%22embedded+inside+silhouette+through+negative+space%22%2C%0A++++++++++++%22readability%22%3A+%22clear+but+discovered%22%0A++++++++%7D%0A%0A++++def+render%28self%29%3A%0A++++++++return+%22%22%22%0A++++++++Render+as+a+clean+optical+typographic+emblem%3A%0A++++++++iconic+silhouette%2C+flowing+contour+stripes%2C%0A++++++++hidden+readable+word%2C+black+ink+on+pure+white.%0A++++++++%22%22%22&utm_source=github&utm_medium=readme&utm_campaign=awesome-nano-banana-2-1-prompts&utm_content=scifi-book-stripe-typography)** · [Source post](https://x.com/Gdgtify/status/2109182713802707328)

- Author / credit: Gadgetify (@Gdgtify)
- Prompt status: `verbatim`

## Prompt

```text
2x2 grid, 16:9, do this for 4 famous scifi books  class OpticalStripeTypographicSilhouette:
    def __init__(self, topic):
        self.topic = topic
        self.word = derive_short_display_word(topic)
        self.silhouette = infer_iconic_silhouette(topic)

        self.stripe_map = infer_contour_stripe_paths(topic, self.silhouette)
        self.typography = integrate_word_into_body(self.word, self.silhouette)
        self.negative_space = solve_white_space_for_readability(topic)

    def silhouette_system(self):
        return {
            "subject": self.silhouette,
            "style": "flat black-and-white vector silhouette",
            "recognition": "instant at thumbnail scale"
        }

    def stripe_system(self):
        return {
            "paths": self.stripe_map,
            "behavior": "flowing contour bands that describe form",
            "palette": "black stripes on white ground",
            "texture": "none, pure graphic ink"
        }

    def word_system(self):
        return {
            "text": self.word,
            "integration": "embedded inside silhouette through negative space",
            "readability": "clear but discovered"
        }

    def render(self):
        return """
        Render as a clean optical typographic emblem:
        iconic silhouette, flowing contour stripes,
        hidden readable word, black ink on pure white.
        """
```

Prompt source: https://x.com/Gdgtify/status/2109182713802707328

## Sources & attribution

- [Gadgetify](https://x.com/Gdgtify) — [source post](https://x.com/Gdgtify/status/2109182713802707328)

Original media, prompts and post text remain the property of their creators. See [media rights](../MEDIA-RIGHTS.md).

[More Nano Banana 2.1 work on ChatImg →](https://chatimg.ai/prompts/nano-banana-2-1?utm_source=github&utm_medium=readme&utm_campaign=awesome-nano-banana-2-1-prompts)
