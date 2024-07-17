# Conductor
An open-source container platform, written by [Matthew Costa](https://www.ucosty.io) in Rust.

## Terminology

If you're familiar with Kubernetes, then this little cheat sheet should help:

```text
Kubernetes    => Conductor
Control Plane => Controller
Node          => Engine
Pod           => Wagon
Cluster       => Railway
Scheduler     => Dispatcher
kubelet       => engined
kubectl       => trainctl
```

## Project Structure

* `crates/controller` - The Controller server / control plane
* `crates/engined` - The node daemon
* `crates/trainctl` - The trainctl command line interface to the Railway

