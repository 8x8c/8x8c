![a1500x500](https://github.com/user-attachments/assets/b76d2b1b-d314-4dce-85f2-b5869673db7d)

https://www.rust-lang.org/  The rust site. 

https://crates.io/   The other rust site. 


 Objectively, for today,  Rust is god. 

 Rust apps in this repo are as simple as possible. 2 files, cargo.toml and main.rs !! Incredibly easy to feed to Ai in order to audit, incredibly easy to modify. The crates.io deps change version numbers, Rust itself gets updates with time. So a ONE SIMPLE main.rs file is easier to update and upgrade in the future. 
 


Here are some groups- (Some repos are not in any group)


# Group 5 Serpent 

NOTE:: Serpent encryption apps in Rust are NOT easy! No dev seems to have been done to serpent crates when AES beat out the Serpent algo. Nonetheless, Serpent is an interesting algo, in time i will have great serpent apps. 



https://github.com/8x8c/Serpent-1  First working app! This one is in pure rust. (no deps) 

https://github.com/8x8c/basilisk  I forked the only working serpent app i could find! 


# Group 4  Threefish-512 

Different working Threefish-512 file encryption apps. This one is a bit tough, as there is not much out there yet, as Threefish-512 is not so popular. It will take a long time to have the best Threefish-512  apps. The lower versions of the apps will have to be custom made, for now. 




https://github.com/8x8c/threefish-512-v2  Version 2 
 

https://github.com/8x8c/threefish-512  Version 1 Threefish-512 in CTR mode / HMAC-SHA512 / Argon2id. 






# Group 3

A focus on high security / extremely user friendly encryption apps. NOTE- BECAUSE the apps all use atomic file overwrite, in order to be safe on mac or windows some slight code changes would be required. As such, the apps here are for LINUX. If you are on windows or mac, feed the code to Ai and tell it you are on mac or windows and need atomic file operation updated - or-  use apps from Group 2.

Group 3 has 3 versions of xcrypt - each version is a different algo. 

https://github.com/8x8c/xcrypt-AES-256-GCM-SIV  High security AES-256-GCM-SIV  file encryption for LINUX. 

https://github.com/8x8c/xcrypt-XChaCha20-Poly1305 High security Xchacha20-Poly1305 file encryption for LINUX. 

https://github.com/8x8c/xcrypt_aes High security AES-GCM  file encryption for LINUX. 






# Group 2 
Very nice no-nonsense encryption apps. Each is only 2 files, cargo.toml and main.rs !! As time goes by, the apps will still be good but make sure to check crates.io for updates to the deps in cargo.toml and then have ai make modifications to main.rs in order to properly implement the new deps. 


https://github.com/8x8c/xchacha A great encryption app made with Rust.

https://github.com/8x8c/AES AES-256-GCM encryption app made with Rust.

https://github.com/8x8c/OTP-elite One Time Pad made with Rust.

https://github.com/8x8c/keygen Awesome Key maker made in Rust.

https://github.com/8x8c/ezAES AES with hard coded key so it runs on ONE command! 

https://github.com/8x8c/keygen32 Deterministic 32 byte key maker in Rust

https://github.com/8x8c/Xchacha20-elite  Xchacha20-poly1305 encryption made with Rust. 

https://github.com/8x8c/AES-elite AES encryption made with Rust. Elite design choices.

https://github.com/8x8c/otp-osd one time pad - one step down- a custom encryption Rust cli app

https://github.com/8x8c/filecrypt AES-256-GCM + password-based key derived with Argon2id.

 https://github.com/8x8c/Feistel-Network-File-Encryption- A basic encryption app


# Group1 
 Archived repos. Lots of imageboards and simple crypto apps. Older stuff, there is some good code in there tho. 













