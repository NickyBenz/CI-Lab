build:
	cargo build
run: 
	cargo run 
test: 
	cargo test 

fmt:
	@rustup add component rustfmt 
	cargo fmt  
clean:
	cargo clean

lint:
	@rustup add component clippy 
	cargo clippy 

all:
	cargo build 
	cargo test 
	cargo fmt
	cargo clean  