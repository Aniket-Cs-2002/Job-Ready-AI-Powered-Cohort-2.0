# 🌍 How Does the Internet Work?

The **Internet** works by connecting devices like phones, tablets, and computers through **Wi-Fi** or **mobile data**.  
When you use a **web browser** to visit a website, you type a **URL** (like `www.sheryians.com`) which the browser translates into an **IP Address** using the **Domain Name System (DNS)**.  

Your device then sends a **request** to the website’s server using this IP address. The server processes the request and sends back the website’s data (**text, images, videos, etc.**) to your device.  
This data is broken into **small packets** that travel through networks and routers before reaching your device, where they are **reassembled** to display the website.  

---

## 📦 Data Packets Transfer Process

### 1️⃣ Request Initiation
Jab aap apne phone pe ek website open karte ho, aapka **browser ek request bhejta hai server ko**. Yeh request **data packets** ke roop mein hoti hai.

### 2️⃣ Packet Creation
Aapka phone (client) ek **request packet** banata hai. Is packet mein hota hai:
- **Source IP Address** → Aapke phone ka IP address  
- **Destination IP Address** → Website ke server ka IP address  
- **Data** → Request ka actual data (jaise URL)  

### 3️⃣ Routing
Packet pehle **router** tak jata hai. Router decide karta hai ki packet ko aage kahan bhejna hai. Yeh process **hop-by-hop** hoti hai.

### 4️⃣ Internet Backbone
Packets **internet backbone** ke zariye travel karte hain — yeh ek **high-speed global network** hota hai jo packets ko duniya bhar mein le jata hai.

### 5️⃣ Reaching the Server
Packets finally **destination server** tak pohch jate hain.  
Server request ko process karta hai aur **response packets** banata hai.

### 6️⃣ Return Journey
Response packets server se wapas aapke device tak aate hain, **same routing process** se guzarte hue.

### 7️⃣ Reassembly
Aapka phone **packets ko reassemble** karta hai aur aapko website display hoti hai.

---

## 📱 Example: Loading a Web Page
1. You type a **URL** in your browser.  
2. Your phone **breaks the request into packets**.  
3. Packets travel through your **local network → router**.  
4. Router sends packets to your **ISP (Internet Service Provider)**.  
5. ISP routes packets through the **internet backbone**.  
6. Packets reach the **website’s server**.  
7. Server processes request and sends back **response packets**.  
8. Packets travel back through the **internet backbone → ISP → router**.  
9. Your phone **reassembles the packets** and displays the **web page**.  

---

# 📖 History of the Web

- **Web 1.0** → Static web pages, read-only.  
- **Web 2.0** → Interactive, dynamic, user-generated content.  
- **Web 3.0** → Semantic web, AI + machine learning integration.  

---

# 🔑 IP and MAC Addresses

- **IP Address** → Unique address for internet communication (e.g., `192.168.1.1`)  
- **MAC Address** → Unique hardware address for devices in a local network (e.g., `00:1A:2B:3C:4D:5E`)  

---

# 🌐 What is DNS?

**DNS** stands for **Domain Name System** → It’s like the **phonebook of the internet**.

---

## ❓ Why Do We Need DNS?
- **Human-Friendly Names** → Easier to remember `www.sheryians.com` than `192.0.2.1`.  
- **IP Address Mapping** → Translates domain names into IP addresses so browsers can load resources.  

---

## ⚙️ How DNS Works

### 1️⃣ You Type a URL 🌍
You enter a **URL** (e.g., `www.sheryians.com`) in your browser.  

### 2️⃣ DNS Resolution Process 🔍
- **Local DNS Cache** → Device checks if it already knows the IP.  
- **ISP DNS Server** → If not found, request goes to your ISP’s DNS server.  
- **Root DNS Server** → Directs to the correct Top-Level Domain (TLD) server (.com, .org, etc.).  
- **TLD DNS Server** → Directs to the authoritative DNS server.  
- **Authoritative DNS Server** → Returns the **IP address** of the domain.  

### 3️⃣ Browser Makes the Connection 🖥️
Your browser now uses the **IP address** to connect to the **web server** and fetch the requested page.  

---
✅ **In short:** Internet works through **packets, routing, DNS, and servers** — all working together to display information on your device. 🚀
