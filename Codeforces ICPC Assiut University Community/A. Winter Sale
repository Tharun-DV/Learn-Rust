use std::io;

fn main() {
    let mut num1: String = String::new();

    io::stdin().read_line(&mut num1).expect("Error");

    let parts: Vec<&str> = num1.trim().split_whitespace().collect();
    let mut num1: i64 = parts[0].parse::<i64>().expect("Error");
    let mut num2: i64 = parts[1].parse::<i64>().expect("Error");
    num2 = num2 * 100;
    num1 = 100 - num1;
    let ans: f32 = num2 as f32 / num1 as f32;
    println!("{:.2}", ans);
}
