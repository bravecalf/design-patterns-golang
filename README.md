# design-patterns-golang
🐝🐝Design Patterns in Golang.

# 一、创建型模式
## 1. 工厂方法模式
在工厂模式中，我们在创建对象时不会对客户端暴露创建逻辑，并且是通过使用一个共同的接口来指向新创建的对象。

[factory design pattern](./creational/factory)

## 2. 抽象工厂模式
在抽象工厂模式中，接口是负责创建一个相关对象的工厂，不需要显式指定它们的类。每个生成的工厂都能按照工厂模式提供对象。

[abstract factory design pattern](./creational/abstract_factory)

## 3. 单例模式
这种模式涉及到一个单一的类，该类负责创建自己的对象，同时确保只有单个对象被创建。这个类提供了一种访问其唯一的对象的方式，可以直接访问，不需要实例化该类的对象。

[singleton design pattern](./creational/singleton)

## 4. 建造者模式
建造者模式（Builder Pattern）使用多个简单的对象一步一步构建成一个复杂的对象。一个 Builder 类会一步一步构造最终的对象。该 Builder 类是独立于其他对象的。

[builder design pattern](./creational/builder)