## projects

### marketplace monitor
monitors a major secondhand marketplace for new listings in real time.
you define your search — it polls continuously, filters out irrelevant posts using a banword list, and fires an instant notification the moment something matching shows up.

> real-time polling · banword filtering · instant notifications

---

### preisscout
> instant price intelligence — powered by statistical filtering

you type a product name. it scrapes all available listings, throws out junk (accessories, €1 bait, price anomalies), and gives you clean numbers:

```
min / max / median / avg + top 5 cheapest with links
```

filters work in layers — title relevance first, then a dynamic price floor, then IQR outlier removal. what comes out is actually useful.

> scraping · statistics · CLI tool
