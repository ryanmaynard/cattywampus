<p align="center">
  <img height="200" src="./cattywampus.png">
</p>

![badge](./badge.svg)

# Cattywampus
## Minimal Parking Page for Dokku


### Usage

##### Clone repo

```
$ git clone git@github.com:ryanmaynard/cattywampus.git project-name
$ cd project-name
```

##### Add header and/or subheader

```
<div class="splash">
	<h1 class="splash-head">Cattywampus</h1>
	<p><a class="pure-button pure-button-primary" href="external-url">Coming Soon</a></p>
</div>
```
### Options

##### Select a gradient
Head to [UI Gradients][uigradients] to grab some color values. Copy the CSS and place it in `main.css`
 
```
.splash-container {
    background: #fd746c;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to top, #ff9068, #fd746c);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to top, #ff9068, #fd746c); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
```
##### Analytics 
Add analytics if you want to place a retargeting pixel

```
<footer>
  <script>
    // Analytics 

  </script>
</footer>
```
### Credit
[Indrashish Ghosh][ghosh] for making [uiGradients][uigradients].

### License

[MIT][mit] - [MIT TLDR][mit-tldr]

[uigradients]: https://uigradients.com/
[ghosh]: https://github.com/ghosh
[mit]: ./LICENSE
[mit-tldr]: https://tldrlegal.com/license/mit-license