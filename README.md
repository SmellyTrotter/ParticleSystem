# ParticleSystem
Three.js Particle System devries from stemkoski's ParticleEngine.  
基于three.js的粒子系统，内置火焰，雪花，星轨，萤火虫，爆炸等特效，可以根据自己需要调整参数。 

![演示地址](https://dev.xingway.com/experiments/threejs/particle-system/ "ParticleSystem")

作者：LucasLight
链接：https://www.jianshu.com/p/40ba812dd973
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
[![ParticleSystem](https://raw.githubusercontent.com/imokya/ParticleSystem/master/src/img/preview.png)](https://dev.xingway.com/experiments/threejs/particle-system/)

### 使用
```
const particleSystem = new ParticleSystem()
particleSystem.emitter = new FlameEmitter()
particleSystem.start()
scene.add(particleSystem.mesh)
```
### 构建
```
npm run dev
npm run build
```
