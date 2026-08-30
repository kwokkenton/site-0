+++
template = "homepage.html"
+++

<style>
.homepage-hero {
    text-align: center;
    padding: 2rem 0;
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 3rem;
    align-items: center;
    max-width: 1000px;
    margin: 0 auto;
}
.homepage-hero-title {
    font-size: 3rem;
    margin-top: 1rem;
    margin-bottom: 1rem;
    font-family: Roca, sans-serif;
}

.homepage-hero-subtitle {
    font-size: 1.25rem;
    margin-bottom: 1rem;
}

/* Mobile */
@media (max-width: 700px) {
    .homepage-hero {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .homepage-hero-image img {
        margin: 0 auto;
    }

    .homepage-hero-content {
        text-align: center;
    }
}
</style>

<div class="homepage-hero">
    <div class="homepage-hero-image">
        <img src="head.JPG" alt="Kenton">
    </div>
    <div class="homepage-hero-content">
        <h1 class="homepage-hero-title">Hiya! I'm Kenton</h1>
        <p class="homepage-hero-subtitle">With a background in physics and biomedical imaging, I hope to develop science and technology for a healthier world. I'm currently a PhD student at the University of Cambridge and I grew up in Hong Kong.</p>
        <p>I am passionate about sharing the joy of being curious and being courageous whilst doing it!</p>
    </div>
</div>


My main interests are in **biophotonics**, the **imaging of disease**, **computer vision** and **medical device development**. I'm passionate about the process of turning ideas into reality and have joint academic and industry experience. Some of my projects are [here](@/projects/_index.md).

Besides my technical work, I enjoy doing **scientific communication**. I hope to use this platform to encourage curiosity, learning, and show how cool science and technology is. My social media page has gained 4000+ followers and over 1.8 M views. Check out more [here](@/projects/_index.md).
<!-- 
# Features

- [Light, dark, and auto themes](@/posts/configuration.md#theme-mode-theme)
- [Projects page](@/projects/_index.md)
- [Talks page](https://not-matthias.github.io/talks/)
- [Analytics (GoatCounter, Umami)](@/posts/configuration.md#analytics)
- [Social media links](@/posts/configuration.md#socials)
- [MathJax rendering](@/posts/math-symbol.md)
- [Taxonomies](/apollo/tags)
- [Custom homepage](@/posts/custom-homepage.md)
- [Comments](@/posts/configuration.md#comments-comment)
- [Search functionality](@/posts/configuration.md#search-build-search-index)
- [Characters](@/posts/configuration.md#character-components)

Checkout all the [options you can configure](@/posts/configuration.md) and the [example pages](@/posts/_index.md). -->