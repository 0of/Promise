# Promise
c++ implemented Promise

# Features
- C++03 compliant
- isolated `shared_ptr<T>` & `type_traits` implementations included
- error is transferred through exception pointer
- support `Promisee` to resolve/reject specific promise

# Constraints
- only runs on **Windows**
- messages are delivered via **Windows** thread message queue
