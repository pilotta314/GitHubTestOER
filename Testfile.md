# Tests:

### Collapse:

<details>
  <summary markdown="span">Solution down here.</summary>

    Great, you found the solution!

</details>

### Pictures

![Sample Picture](media/markdown_logo.png "Markdown Logo")

![Definition der Kraft](https://lx3.mint-kolleg.kit.edu/onlinekursphysik/html/1.3.1/Physikkurs/kraefte_definitionmessung/images/WaageGGundnGG.png)

### Video:
[![Video mit Bild](https://lx3.mint-kolleg.kit.edu/onlinekursphysik/html/1.3.1/Physikkurs/kraefte_definitionmessung/images/WaageGGundnGG.png)](https://media.bibliothek.kit.edu/world/2020/DIVA-2020-436_mp4.mp4)

![Sample Video](media/markdown_video.mp4 "GitLab sample video")

#### Audio:

![Sample Audio](media/markdown_audio.mp3 "GitLab sample audio")



### Table:

|    Features     | GitLab       | GitHub          | Moodle         |
|-----------------|:-------------|:---------------:|---------------:|
| Tables          | check        |                 |                |
| Collapse        |              |       middle    |                |
| ...             |              |                 |     right      |

### Code-Blocks:

**In-line:** 
`Example` code block in-line.

**Fenced:**
```python
def hello
    print("Hello World!")
end
```
### Backgorund coloring:

<div class="panel panel-info">

Sample Info-Panel

</div>

<div class="alert alert-block alert-success">
  <b> Achtung, wichtig! </b>
</div>
 
`only in one line possible`

```
multi
lines
```

[+green=correct+]

[-red=false-]


### Checkbox:

- [x] Completed task
- [ ] Incomplete task
  - [ ] Sub-task 1
  - [x] Sub-task 2
  - [ ] Sub-task 3


### Links:

Sample [Link](https://www.youtube.com/embed/enMumwvLAug)

### Schriftgröße

<h1> Dieser Text ist riesig</h1>
<h6> Dieser Text ist winzig
  <br>und geht über mehrere Zeilen
</h6>

### Formeln

<math> 
   x^2
</math>

```math
\sum_{i=1}^{n}
\Phi(x_i^2)
```


[latex]1+2=3[/latex]

<math>
    <mrow> 
        <mn>1</mn><mo>+</mo><mn>2</mn>
        <mo>=</mo><mn>3</mn> 
    </mrow> 
</math>

<script src="plugin/math/math.js"></script>
<script>
  Reveal.initialize({
    math: {
      mathjax: 'https://cdn.jsdelivr.net/gh/mathjax/mathjax@2.7.8/MathJax.js',
      config: 'TeX-AMS_HTML-full',
      // pass other options into `MathJax.Hub.Config()`
      TeX: { Macros: { RR: "{\\bf R}" } }
    },
    plugins: [ RevealMath ]
  });
</script>

### Lists

1. First
1. Second
   1. ordered
   1. sub-list
1. Third
   1. ordered
   1. sub-list
1. Fourth
   - unordered
   - sub-list
1. Last one
