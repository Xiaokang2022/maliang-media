<h1 align="center">maliang-media</h1>

<p align="center"><a title="Official Website" href="https://xiaokang2022.github.io/maliang/">https://xiaokang2022.github.io/maliang/</a></p>

<p align="center">Extension package of <code>maliang</code> to play media files</p>

<p align="center">
<a href="https://github.com/Xiaokang2022/maliang-media/releases"><img alt="Version" src="https://img.shields.io/github/v/release/Xiaokang2022/maliang-media?include_prereleases&logo=github&label=Version" title="Latest Version" /></a>
<a href="https://pypistats.org/packages/maliang-media"><img alt="Downloads" src="https://img.shields.io/pypi/dm/maliang-media?label=Downloads&logo=pypi&logoColor=skyblue" title="Downloads" /></a>
<a href="https://pepy.tech/project/maliang-media"><img alt="Total Downloads" src="https://img.shields.io/pepy/dt/maliang-media?logo=pypi&logoColor=gold&label=Total%20Downloads" title="Total Downloads" /></a>
<a href="https://github.com/Xiaokang2022/maliang-media"><img alt="Size" src="https://img.shields.io/github/languages/code-size/Xiaokang2022/maliang-media?label=Size&logo=github" title="Code Size"/></a>
<br/>
<a href="https://github.com/Xiaokang2022/maliang-media/watchers"><img alt="Watchers" src="https://img.shields.io/github/watchers/Xiaokang2022/maliang-media?label=Watchers&logo=github&style=flat" title="Watchers" /></a>
<a href="https://github.com/Xiaokang2022/maliang-media/forks"><img alt="Forks" src="https://img.shields.io/github/forks/Xiaokang2022/maliang-media?label=Forks&logo=github&style=flat" title="Forks" /></a>
<a href="https://github.com/Xiaokang2022/maliang-media/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/Xiaokang2022/maliang-media?label=Stars&color=gold&logo=github&style=flat" title="Stars" /></a>
<a href="https://github.com/Xiaokang2022/maliang-media/issues"><img alt="Issues" src="https://img.shields.io/github/issues/Xiaokang2022/maliang-media?label=Issues&logo=github" title="Issues" /></a>
<a href="https://github.com/Xiaokang2022/maliang-media/pulls"><img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/Xiaokang2022/maliang-media?label=Pull%20Requests&logo=github" title="Pull Requests" /></a>
<a href="https://github.com/Xiaokang2022/maliang-media/discussions"><img alt="Discussions" src="https://img.shields.io/github/discussions/Xiaokang2022/maliang-media?label=Discussions&logo=github" title="Discussions" /></a>
</p>

<p align="center">
<a href="https://github.com/Xiaokang2022/maliang-media/pulse"><img alt="Insights" src="https://repobeats.axiom.co/api/embed/0be944bbd1d27b25b519ea2ac7ffcdfbc98369fb.svg" /></a>
</p>

<p align="center">
    <a href="https://star-history.com/#Xiaokang2022/maliang-media&Date">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Xiaokang2022/maliang-media&type=Date&theme=dark" />
            <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Xiaokang2022/maliang-media&type=Date" />
            <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Xiaokang2022/maliang-media&type=Date" />
        </picture>
    </a>
</p>

📦 Installation
----------------

```shell
pip install maliang-media
```

### 👀 Preview

> [!WARNING]  
> The sample video from: https://github.com/Xiaokang2022/maliang-demos/tree/main/assets/videos. Please note that the video is for testing purposes only and may not be used for commercial purposes!

![preview-1](./preview-1.png)

![preview-2](./preview-2.png)

```python
import maliang
from maliang import media

root = maliang.Tk(title="maliang-media")
cv = media.VideoCanvas(free_anchor=True, keep_ratio="min", controls=True)
cv.place(width=1280, height=720, x=640, y=360, anchor="center")
cv.open("your_video_file.mp4")
root.mainloop()
```
