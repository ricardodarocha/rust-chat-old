# Rust Chat

This is not the most up to date approach to write a chat in Rust, But I'm very hapy that I could run it without any effort, and It still working!!

Greate, but most inpressive is the [Rust Class](http://nbaksalyar.github.io/2015/07/10/writing-chat-in-rust.html) that @nbaksalyar give us

The detailed tutorial is available in a series of blog posts:

* [Rust in Detail: Writing Scalable Chat Service from Scratch](http://nbaksalyar.github.io/2015/07/10/writing-chat-in-rust.html) ([中国](http://markindev.github.io/2016/02/15/Rust-in-Details-Part-1/), [한국어](http://blog.naver.com/futurewave01/220539095123), на [русском](https://habrahabr.ru/post/268609/)).
* [Rust in Detail, Part 2](http://nbaksalyar.github.io/2015/11/09/rust-in-detail-2.html) (на [русском](https://habrahabr.ru/post/278635/)).


# Try it

```Shell 
git clone this or those repository
cargo run 
```
Then the browser and look for the Developer Tools, try to put this code into console.log
```Just
ws = new WebSocket('ws://127.0.0.1:10000');

ws.onmessage = function (event) {
    console.log('Received response: ', event.data);
};
ƒ (event) {
    console.log('Received response: ', event.data);
}
```

Open two browser to experiment talking to each other

ws.send('Hey there!')
