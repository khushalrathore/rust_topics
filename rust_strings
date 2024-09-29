use unicode_segmentation::{self, UnicodeSegmentation};
fn main() {
    let mut s1 = String::new();

    s1.push_str("Hello, World 1");

    let s2 = "Hello, World 2";

    let s3 = s2.to_string();

    let s4 = String::from("Hello, World 4");

    let s5 = format!("{}{}", s1, s2);

    println!("{}\n{}\n{}\n{}\n{}", s1, s2, s3, s4, s5);

    for b in "नमस्ते".bytes() {
        print!("{} ", b);
    }
    println!("");
    for c in "नमस्ते".chars() {
        print!("{} ", c);
    }
    println!("");
    for g in "नमस्ते".graphemes(true) {
        print!("{} ", g);
    }
}
