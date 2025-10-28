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
