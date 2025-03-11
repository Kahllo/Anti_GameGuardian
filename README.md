# Anti_GameGuardian
🛡️ Anti_GameGuardian is a native C++ library that detects and blocks Game Guardian


## 🚀 Features  
✅ **Detects and prevents Game Guardian memory scans**  
✅ **Runs automatically – no JNI function calls required**  
✅ **Precompiled `.so` files for easy integration**  
✅ **Lightweight, efficient, and stealthy anti-cheat protection**  

## 🔧 How to Integrate  

### 1️⃣ **Download the Precompiled `.so` Files**  
📥 Get the latest release from [Releases](https://github.com/YOUR-USERNAME/Anti_GameGuardian/releases).  

---

### 2️⃣ **Add `.so` Files to Your Project**  
Place the .so folders in  your app’s `jniLibs/` folder:  
Example : 

<img width="251" alt="image" src="https://github.com/user-attachments/assets/ebf83581-0105-4b1f-b781-611d2375a415" />


### 3️⃣ **Load the ggdetection library**

```<Java>
//  System.loadLibrary("ggdetection")
```
