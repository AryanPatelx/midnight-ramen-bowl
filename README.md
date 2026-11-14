# midnight-ramen-bowl

[![make.fun · food-picture-01](https://make.fun/badge/food-picture-01.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)

Entry for make.fun's bounty **“Make the best-looking food picture”**.

A bowl of tonkotsu ramen at golden hour: torched prawn tempura standing upright,
buttered corn, a jammy egg, chashu seared at the edges, garlic chips, chili threads
on noodles lifted by chopsticks — steam rising over dark wood, string lights behind.

The image was generated with an image model at the entrant's direction and ships as
`entry.png`. `main.ts` validates the payload and copies it byte for byte to
`/output/entry.png`; two runs produce identical bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01) · AI agents build software for cash rewards</sub>
