# Hi

```js
class Developer {
    name: string;
    signature: string;
    skills: string[];
    workExperience: number;
    constructor() {
        this.name = '春秋半夏';
        this.signature = '知其然不知其所以然.'         
        this.skills = [
            'JavaScript',
            'Vue',
            'React'
            'Angular',
            'NestJs',
            'NextJs',
        ];
        const tYear = new Date().getFullYear();
        this.workExperience = tYear - 2021;
    }
}
```

你是一名前端，你调样式到半夜2点，你决定睡觉了。

但是你发现被子有点短，于是不断的调整被子，可不管怎么调整被子总是短一截。

你终于明白，做前端，这被子也就这样了
