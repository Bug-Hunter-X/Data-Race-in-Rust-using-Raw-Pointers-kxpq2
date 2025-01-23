This repository demonstrates a common error in Rust: data races caused by unsafe code. The `bug.rs` file contains the buggy code, which uses a raw pointer to modify a vector after it has been borrowed mutably. This leads to undefined behavior. The `bugSolution.rs` file shows how to safely modify the vector using proper Rust ownership and borrowing.