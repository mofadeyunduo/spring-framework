# Ioc 容器原理

控制反转：把创建对象的权利交给框架。

# Bean

## 资源接口

- Resource 表示资源，这里指 Bean 资源
- ResourceLoader 定义了资源加载方法

## Bean 定义

- BeanDefinition 表示 Bean 定义

## Bean 读取

- BeanDefinationReader 用 ResourceLoader 中读取 Bean 定义 

# Bean 工厂

- BeanFactory 负责获取 Bean，入口是 refresh
- ApplicationContext 增强了 BeanFactory，提供资源加载等功能
- AbstractApplicationContext 继承子 ApplicationContext，定义了加载 Bean 的流程


## 抽象类


## 读取 Bean，创建 Bean 工厂

- ResourceLoader 生成 Resource
- BeanDefinationReader 利用 ResourceLoader 加载 Bean
