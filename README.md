## projects

### marketplace monitor
monitors a major secondhand marketplace for new listings in real time.
you define your search — it polls continuously, filters out irrelevant posts using a banword list, and fires an instant notification the moment something matching shows up.

> real-time polling · banword filtering · instant notifications

---
### briefik (in progress)
> your digital shield against the "yellow envelope" — powered by ai

snap a photo of any german official letter. it decodes the "beamtendeutsch" (bureaucratic jargon), identifies critical deadlines, and transforms complex legal paragraphs into a clear, actionable roadmap in your native language.
Designed for individuals who lack confidence in their German language skills.

currently in the final testing phase and undergoing active refinement.

```text
urgency traffic light / actionable tasks / deadlines extraction
```


### preisscout
> instant price intelligence — powered by statistical filtering

you type a product name. it scrapes all available listings, throws out junk (accessories, €1 bait, price anomalies), and gives you clean numbers:

```
min / max / median / avg + top 5 cheapest with links
```

filters work in layers — title relevance first, then a dynamic price floor, then IQR outlier removal. what comes out is actually useful.

> scraping · statistics · CLI tool
