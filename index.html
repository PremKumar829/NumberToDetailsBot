import requests
import json
import time
import sys
import os

def clear_screen():
    os.system('clear')

def type_text(text, delay=0.03):
    for char in text:
        print(char, end='', flush=True)
        time.sleep(delay)
    print()

def hacker_intro():
    clear_screen()
    print("\033[1;32m")  # Green color
    type_text("╔══════════════════════════════════════════════════╗")
    type_text("║               OSINT BY PRINCIPAL                  ║")
    type_text("║           PHONE NUMBER LOOKUP                   ║")
    type_text("║             DEVELOPER: @PRIMEXTOUR                ║")
    type_text("╚══════════════════════════════════════════════════╝")
    print("\033[1;36m")  # Cyan color
    type_text("[+] Initializing Phone Lookup System...")
    time.sleep(1)
    type_text("[+] Loading Database Modules...")
    time.sleep(1)
    type_text("[+] Connecting to Intelligence Network...")
    time.sleep(1)
    type_text("[+] Establishing Secure Connection...")
    time.sleep(1)
    print("\033[0m")  # Reset color

def fetch_number_info(number):
    url = f"https://vippanels.x10.mx/numapi.php?action=api&key=month&term={number}"
    
    try:
        print(f"\033[1;33m[~] Scanning Target: {number}\033[0m")
        time.sleep(1)
        type_text(f"[~] Querying Database...", 0.02)
        
        response = requests.get(url, timeout=10)
        
        if response.status_code == 200:
            print("\033[1;32m[+] Database Response Received\033[0m")
            time.sleep(0.5)
            return response.json()
        else:
            print(f"\033[1;31m[!] Database Error: HTTP {response.status_code}\033[0m")
            return None
            
    except requests.exceptions.RequestException as e:
        print(f"\033[1;31m[!] Network Error: {e}\033[0m")
        return None
    except json.JSONDecodeError:
        print("\033[1;31m[!] Invalid Response Format\033[0m")
        return None

def display_results(data, number):
    print("\n" + "="*60)
    print("\033[1;35m              PHONE NUMBER LOOKUP - RESULTS")
    print("="*60 + "\033[0m")
    
    if not data or 'data' not in data or not data['data']:
        print("\033[1;31m[!] NO DATA FOUND FOR THIS NUMBER\033[0m")
        return
    
    records = data['data']
    
    for idx, record in enumerate(records, 1):
        print(f"\033[1;32m📄 Record #{idx}")
        
        # Define display order and mapping
        display_fields = [
            ('name', '👤 Name'),
            ('mobile', '📱 Mobile'),
            ('fname', '👨‍👩‍👦 Father'),
            ('alt', '📞 Alt Number'),
            ('address', '🏠 Address'),
            ('id', '🆔 Aadhar'),
            ('circle', '🌐 Circle')
        ]
        
        # Filter available fields (exclude credit field)
        available_fields = []
        for field_key, field_display in display_fields:
            if field_key in record and record[field_key] and str(record[field_key]).strip() not in ['', 'null', 'None']:
                available_fields.append((field_key, field_display, record[field_key]))
        
        if not available_fields:
            print("\033[1;31m└ ❌ No data available\033[0m")
            continue
        
        # Display available fields
        for i, (field_key, field_display, value) in enumerate(available_fields):
            prefix = "├" if i < len(available_fields) - 1 else "└"
            
            # Clean address field (remove !! separators)
            if field_key == 'address':
                value = value.replace('!!', ', ').replace('!NA!', '').replace('!', ' ')
            
            print(f"\033[1;32m{prefix} {field_display}: {value}\033[0m")
            time.sleep(0.1)
        
        print()  # Empty line between records

def hacker_animation():
    animations = [
        "[▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] 100% SCAN COMPLETE",
