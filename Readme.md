# **gping master 🚀**

**Ping, but with a graph. Your ultimate network monitoring tool.**

gping master is a powerful, cross-platform command-line tool that enhances the standard ping utility by displaying a real-time graph of the ping latency. It's perfect for network administrators, developers, and anyone who needs a quick and visual way to monitor network connectivity and performance.

*(A short GIF demonstrating gping master's graphical output would be perfect here\!)*

## **✨ Key Features**

* **Real-time Latency Graph:** Visualize ping times directly in your terminal.  
* **Cross-Platform:** Runs seamlessly on Linux, macOS, and Windows.  
* **Simple & Intuitive:** If you know how to use ping, you're ready to go.  
* **Customizable:** Control ping intervals, buffer sizes, and more with simple flags.  
* **Lightweight:** A single, fast binary with minimal dependencies.  
* **Color-coded Output:** Easily spot high latency or packet loss.

## **📦 Installation**

### **Homebrew (macOS & Linux)**

brew install gping-master

### **Scoop (Windows)**

scoop install gping-master

### **Cargo (Rust Package Manager)**

cargo install gping-master

### **Binaries**

Pre-compiled binaries are available on the [Releases page](https://www.google.com/search?q=https://github.com/your-username/gping-master/releases).

## **Usage**

Ping a host with default settings:

gping master google.com

View all available options for customization:

gping master \--help

USAGE:  
    gping master \[OPTIONS\] \<host\>

ARGS:  
    \<host\>    The host to ping.

OPTIONS:  
    \-i, \--interval \<INTERVAL\>    Ping interval in milliseconds \[default: 200\]  
    \-b, \--buffer \<BUFFER\>        Number of pings to display in the graph \[default: 60\]  
    \-h, \--help                   Print help information  
    \-V, \--version                Print version information

## **🤝 Contributing**

Contributions are welcome\! Please feel free to fork the repository, create a feature branch, and open a pull request. Check the [open issues](https://www.google.com/search?q=https://github.com/your-username/gping-master/issues) to see what you can help with.

## **📜 License**

This project is licensed under the MIT License \- see the LICENSE.md file for details.

Made with ❤️ and Rust.