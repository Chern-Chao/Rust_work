mod mod_01{
    pub fn print_a_z(){
        for i in b'a'..=b'z'{
        println!("{}\n", i as char);
    }
        for i in b'A'..=b'Z'{
        println!("{}\n", i as char);
}
}
}
mod mod_02{
    pub fn print_a_z2(){
        for i in b'A'..=b'Z'{
        println!("{}\n", i as char);
    }
    
        for i in b'a'..=b'z'{
        println!("{}\n", i as char);
}
}
}
fn main(){
    mod_01::print_a_z();
    mod_02::print_a_z2();
}
