[⬅ Main Page](https://github.com/e4jet/dsop)

# Episode 3: Storage Provisioning in Kubernetes

## [Video Link ⬈](https://www.youtube.com/watch?v=BM_QyqnRsMg)

## Description

Provide an overview of the following:

* __Volume Provisioning (Direct Volume Reference)__
  * Simple and Easy to Manage, especially for an IT Generalist
  * Tightly couples the Pod or Pod Template to a cluster implementation
  * Opaque with regard to the cluster itself (ie: no way to list volumes using kubectl)
* __Persistent Volume Provisioning__
  * Introduces a Layer of Abstraction using 2 objects
    * Persistent Volume - describes storage
    * Persistent Volume Claim - reserves a Persistent Volume
  * Decouples Pod and Pod Templates from the cluster implementation
* __Dynamic Persistent Volume Provisioning (Dynamic Volume Provisioning)__
  * Policy Based Storage Management
  * Self Service Provisioning

## Links

* [Kubernetes Documentation: Storage](https://kubernetes.io/docs/concepts/storage/)
* [Project Dory](https://github.com/hpe-storage/dory)

## Diagrams

### Volume Provisioning (Direct Volume Reference)

#### Manual Provisioning

![1](images/1.png)

![2](images/2.png)

![3](images/3.png)

#### Automatic Provisioning using Dory

![4](images/4.png)

![5](images/5.png)

![6](images/6.png)

### Persistent Volume Provisioning

#### Manual Pre-provisioning

![1](images/1a.png)

![2](images/2a.png)

![3](images/3a.png)

![4](images/4a.png)

#### Demand based Manual Provisioning

![1](images/1b.png)

![2](images/2b.png)

![3](images/3b.png)

![4](images/4b.png)

![5](images/5b.png)

#### Just In Time Provisioning using Dory

![1](images/1c.png)

![2](images/2c.png)

![3](images/3c.png)

![4](images/4c.png)

![5](images/5c.png)

### Dynamic Persistent Volume Provisioning (Dynamic Volume Provisioning)

![1](images/1d.png)

![2](images/2d.png)

![3](images/3d.png)

![4](images/4d.png)

![5](images/5d.png)

![6](images/6d.png)