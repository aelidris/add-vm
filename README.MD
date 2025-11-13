# 🖥️ Add a Virtual Machine

This guide explains how to download, import, and use the provided virtual machines for the **sysadmin exercises**.

Each virtual machine (VM) contains a system in a specific state that you will use during the exercises.  
VMs are provided for both **x86-64** (Intel/AMD) and **Apple Silicon** chips.

---

## 🧩 Choose the Correct Virtualization Software

- **For x86-64 systems** → use **[VirtualBox](https://www.virtualbox.org)**
- **For Apple Silicon systems** → use **[UTM](https://mac.getutm.app)**

You can download the VMs here:

🔗 [https://assets.01-edu.org/sys](https://assets.01-edu.org/sys)

Each VM name starts with `01_` to avoid conflicts with your own virtual machines.

---

## 🗂️ VirtualBox Instructions (x86-64)

1. Download the archive: **`01_add-vm.tar.gz`**
2. Extract it inside the folder:  
3. Open **VirtualBox**, then select from the menu bar:  
4. Navigate to the extracted folder and open the file **`01_add-vm.vbox`**.
5. The VM should now appear in the list under the name **`01_add-vm`**.

---

## 🍎 UTM Instructions (Apple Silicon)

1. Download the archive: **`01_add-vm.utm.zip`**
2. Create a folder on your Desktop named **`UTM_VMs`**.
3. Extract **`01_add-vm.utm`** into that folder.
4. Open **UTM**, then select from the menu bar:  
5. Navigate to **`01_add-vm.utm`** and select it.  
The VM will appear in the list under the name **`01_add-vm`**.

> **Note:** The `.utm` “files” are actually **directories**, not single files.

---

## 🧠 Snapshots

A **snapshot** is a saved state of your system at a specific point in time — like a backup or version checkpoint.

Imagine making a copy of your document or drawing before editing — that’s essentially what a snapshot does.

### 📚 Examples of Software Using Snapshots
- **Git** → each *commit* is a snapshot
- **Windows System Restore** → restore points
- **macOS Time Machine** → backups
- **Linux LVM** → Logical Volume Manager
- **Filesystems** → Btrfs, ZFS
- **Hypervisors** → VirtualBox, UTM

### 💡 Recommendation
Right after importing your VM, **take a snapshot**.  
That way, you can experiment freely — if anything breaks, you can easily return to the original state.

If you forgot to create a snapshot and want a clean start, simply **delete the VM and its files**, then **import it again** following the steps above.

---

## ✅ Check That the VM Works

Since all later VMs are based on this one, make sure it runs correctly:

1. Start the VM.
2. Shut it down gracefully (not by force).

**Login credentials:**
1. Username: root
2. Password: [single space]
---

### 🧾 Summary

| Platform | File to Download | Software | Extract To | VM Name |
|-----------|------------------|-----------|-------------|----------|
| x86-64 | `01_add-vm.tar.gz` | VirtualBox | `~/VirtualBox VMs` | 01_add-vm |
| Apple Silicon | `01_add-vm.utm.zip` | UTM | `~/Desktop/UTM_VMs` | 01_add-vm |

---

