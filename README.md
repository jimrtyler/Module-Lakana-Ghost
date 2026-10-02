# 👻 Ghost Lakanabaliya Moduli
**PowerShell kan na Windows ni Azure Lakanabaliya Balikɛcogo**

> **Windows endpoints ni Azure sigida la lakanabaliya balikɛ sabatili. ** Ghost b'a di PowerShell kan na balikɛcogo minw bɛ se ka dɛmɛ don ka kabakoyasira siralenw dɔgɔya ni baarakɛminɛnw ni protocol minw t'a la ko tigɛlen ye datugu la.

## ⚠️ Fɔlisen Kunba Minw Ka Kan

**KƆRƆBƆLI KA KAN**: Tuma bɛɛ k'a lajɛ Ghost ma yɔrɔw la min t'a ye baarakɛyɔrɔ ye fɔlɔ. Baarakɛminɛnw datugu bɛ se ka nɔ bila jagokɛlaw ka baara kan.

**LATIGƐLI SI TɛRA YEN**: Hali n'a y'a k'a ye kabakoyasira siralenw ka kulu ma, lakanabaliya baarakɛminɛn si tɛ se k'u bɛɛ dabila. Nin ye lakanabaliya fɛɛrɛ kunba dɔ fɛɛrɛ ye.

**BAARAKƐCOGO NƆFƐ**: Baarakɛ dɔw bɛ se ka nɔ bila sistɛmu baarakɛcogo kan. Aw ye yɔrɔ o yɔrɔ hakilijaliya ka jateminɛ sigilikɛ sanni.

**Ɲɛnamayakɛlaw ka Jateminɛ**: Baarakɛyɔrɔ la, ka hakilijagabɔ kɛ ni lakanabaliya ɲɛnamayakɛlaw ye walasa ka a to yɔrɔw ka bɛn aw ka jɛkulu magolaw ma.

## 📊 Lakanabaliya Yɔrɔ

Ransomware tiɲɛna **siɲɛ $57 miliyari ma san 2025 la**, ɲininikɛlaw y'a jira ko kabakoya minw ka ɲi, u bɛ baara kɛ ni Windows baarakɛminɛn jɔnjɔnw ni labɛnni juguw ye. Kabakoyasira siranin minw ka teli yɛrɛ:

- **90% ka ransomware kow** bɛ RDP baarakɛ juguman kɛ
- **SMBv1 fɛnkɛlaw** ye kabakoyaw kɛ i n'a fɔ WannaCry ni NotPetya
- **Sɛbɛnw ka makrow** tun ye malware dicogo fɔlɔ ye
- **USB kan na kabakoyaw** ka taa a fɛ ka intirinɛti min tigɛra ka tɛmɛ
- **PowerShell juguba** y'a caya kosɔbɛ san laban ninnu na

## 🛡️ Ghost Lakanabaliya Baaraw

Ghost b'a di **Windows balikɛcogo baara 16** ni **Azure lakanabaliya jɛɲɔgɔnya**:

### Windows Endpoint Balikɛcogo

| Baara | Kun | Miiriya |
|----------|---------|----------------|
| `Set-RDP` | Ka Remote Desktop donni ɲɛmɔgɔya | A bɛ se ka nɔ bila yɔrɔjamanba yɔrɔjan ma |
| `Set-SMBv1` | Ka SMB protocol kɔrɔ lakanani | A ka kan kɔrɔba sistɛmuw la |
| `Set-AutoRun` | Ka AutoPlay/AutoRun lakanani | A bɛ se ka nɔ bila baarakɛla nɔɲuman ma |
| `Set-USBStorage` | Ka USB maracogo minɛnw dabila | A bɛ se ka nɔ bila USB baarakɛ tigitigilen ma |
| `Set-Macros` | Ka Office macro kɛcogo lakanani | A bɛ se ka nɔ bila sɛbɛn minw be macro ye nɔ ma |
| `Set-PSRemoting` | Ka PowerShell yɔrɔjan ɲɛmɔgɔya | A bɛ se ka nɔ bila yɔrɔjamanba ma |
| `Set-WinRM` | Ka Windows Remote Management lakanani | A bɛ se ka nɔ bila yɔrɔjamanba ma |
| `Set-LLMNR` | Ka tɔgɔɲɔgɔnyacogo protocol ɲɛmɔgɔya | A ka lakana a datugu ma tuma caman na |
| `Set-NetBIOS` | Ka NetBIOS lakanani TCP/IP kan | A bɛ se ka nɔ bila porogaramu kɔrɔw ma |
| `Set-AdminShares` | Ka jamanakuntigiya tilacogo ɲɛmɔgɔya | A bɛ se ka nɔ bila dosiye yɔrɔjan donni ma |
| `Set-Telemetry` | Ka kunnafoni dalajɛcogo lakanani | A bɛ se ka nɔ bila kɔrɔsili seko ma |
| `Set-GuestAccount` | Ka dunan konte ɲɛmɔgɔya | A ka lakana a datugu ma tuma caman na |
| `Set-ICMP` | Ka ping jaabiw lakanani | A bɛ se ka nɔ bila intirinɛti kɔrɔsili ma |
| `Set-RemoteAssistance` | Ka Remote Assistance ɲɛmɔgɔya | A bɛ se ka nɔ bila dɛmɛbaga baara ma |
| `Set-NetworkDiscovery` | Ka intirinɛti ɲinincogo lakanani | A bɛ se ka nɔ bila intirinɛti ɲininni ma |
| `Set-Firewall` | Ka Windows Firewall ɲɛmɔgɔya | A nafa ka bon intirinɛti lakana la |

### Azure Cloud Lakanabaliya

| Baara | Kun | Mako ka Kan |
|----------|---------|--------------|
| `Set-AzureSecurityDefaults` | Ka Azure AD lakanabaliya jɔnjɔn baara bila | Microsoft Graph yamaruya |
| `Set-AzureConditionalAccess` | Ka donni sariyaw labɛn | Azure AD P1/P2 lisansi |
| `Set-AzurePrivilegedUsers` | Ka konte kubarikɛlaw jateminɛ kɛ | Global Admin yamaruya |

### Jagokɛla Sigilikɛ Sugandili

| Fɛɛrɛ | Baarakɛ | Mako ka Kan |
|--------|----------|--------------|
| **Kɛcogo Nɔgɔya** | Kɔrɔbɔli, sigida dɔgɔmanw | Sigida admin yamaruyaw |
| **Kulu Sariya** | Domain sigidaw | Domain admin, GP ɲɛmɔgɔya |
| **Microsoft Intune** | Cloud ɲɛminɛnw min ma | Intune lisansi, Graph API |

## 🚀 Daminɛ Teliya

### Lakanabaliya Jateminɛ
```powershell
# Ghost moduli dami
Invoke-WebRequest 'https://raw.githubusercontent.com/jimrtyler/Ghost/main/Ghost.ps1' -OutFile .\Ghost.ps1
Get-Content .\Ghost.ps1
. .\Ghost.ps1

# Sisan lakanabaliya yɔrɔ lajɛ
Get-Ghost
```

### Jɔnjɔn Balikɛcogo (K'a Lajɛ Fɔlɔ)
```powershell
# Balikɛcogo kɔrɔba - k'a lajɛ laboratuari sigida la fɔlɔ
Set-Ghost -SMBv1 -AutoRun -Macros

# Yɛlɛmani lajɛ
Get-Ghost
```

### Jagokɛla Sigilikɛ
```powershell
# Kulu Sariya sigilikɛ (domain sigidaw)
Set-Ghost -SMBv1 -AutoRun -GroupPolicy

# Intune sigilikɛ (cloud ɲɛminɛnw min ma)
Set-Ghost -SMBv1 -RDP -USBStorage -Intune
```

## 📋 Sigilikɛ Siralenw

### Sugandi 1: Jigin Nɔgɔya (Kɔrɔbɔli)
```powershell
Invoke-WebRequest 'https://raw.githubusercontent.com/jimrtyler/Ghost/main/Ghost.ps1' -OutFile .\Ghost.ps1
Get-Content .\Ghost.ps1
. .\Ghost.ps1
```

### Sugandi 2: Moduli Sigilikɛ
```powershell
# K'a sigi PowerShell Gallery la (ni a sɔrɔla)
Install-Module Ghost -Scope CurrentUser
Import-Module Ghost
```

### Sugandi 3: Jagokɛla Sigilikɛ
```powershell
# K'a kopi intirinɛti yɔrɔ la ka Kulu Sariya sigi
# K'a labɛn Intune PowerShell sɛbɛnw ka cloud sigi
```

## 💼 Baarakɛ Misali

### Jagokɛla Fitinin
```powershell
# Jɔnjɔn lakanabaliya ni nɔfɛ dɔgɔya
Set-Ghost -SMBv1 -AutoRun -Macros -ICMP
```

### Kɛnɛyako Sigida
```powershell
# HIPAA kan na balikɛcogo
Set-Ghost -SMBv1 -RDP -USBStorage -AdminShares -Telemetry
```

### Wariko Baarakɛminɛnw
```powershell
# Lakanabaliya sanfɛba labɛnni
Set-Ghost -RDP -SMBv1 -AutoRun -USBStorage -Macros -PSRemoting -AdminShares
```

### Cloud-Fɔlɔ Jɛkulu
```powershell
# Intune-ɲɛminɛn sigilikɛ
Connect-IntuneGhost -Interactive
Set-Ghost -SMBv1 -RDP -AutoRun -Macros -Intune
```

## 🔍 Baara Kunnafoniw

### Jɔnjɔn Balikɛcogo Baaraw

#### Intirinɛti Baarakɛminɛnw
- **RDP**: Ka desktop yɔrɔjan donni datugu walima ka port kɛ fɛn wɛrɛ ye
- **SMBv1**: Ka dosiye tilacogo protocol kɔrɔ datugu
- **ICMP**: Ka ping jaabiw dabila jateminɛkɛla
- **LLMNR/NetBIOS**: Ka tɔgɔɲɔgɔnyacogo protocol kɔrɔw datugu

#### Porogaramu Lakanabaliya
- **Macros**: Ka macro kɛcogo datugu Office porogaramuw la
- **AutoRun**: Ka kɛcogo yɛrɛmahɔrɔnya dabila media bɔlenw la

#### Yɔrɔjan Ɲɛmɔgɔya
- **PSRemoting**: Ka PowerShell yɔrɔjan taabolo datugu
- **WinRM**: Ka Windows Remote Management dabila
- **Remote Assistance**: Ka Remote Assistance jɛɲɔgɔnyajɛw datugu

#### Donni Lakanani
- **Admin Shares**: Ka C$, ADMIN$ tilacogo datugu
- **Guest Account**: Ka dunan konte donni datugu
- **USB Storage**: Ka USB minɛn baarakɛ dabila

### Azure Jɛɲɔgɔnya
```powershell
# Ka jɛɲɔgɔnya kɛ Azure tenant na
Connect-AzureGhost -Interactive

# Ka lakanabaliya labɛnniw bila baara la
Set-AzureSecurityDefaults -Enable

# Ka donni sigida labɛn
Set-AzureConditionalAccess -BlockLegacyAuth -RequireMFA

# Ka baarakɛla kubarikɛlaw jateminɛ kɛ
Set-AzurePrivilegedUsers -AuditOnly
```

### Intune Jɛɲɔgɔnya (Kura v2 la)
```powershell
# Ka jɛɲɔgɔnya kɛ Intune na
Connect-IntuneGhost -Interactive

# Ka sigi Intune sariyaw fɛ
Set-IntuneGhost -Settings @{
    RDP = $true
    SMBv1 = $true
    USBStorage = $true
    Macros = $true
}
```

## ⚠️ Miiriya Kunba

### Kɔrɔbɔli Mako Minw Ka Kan
- **Laboratuari Sigida**: K'a lajɛ yɔrɔ bɛɛ sigida dantigɛlen na fɔlɔ
- **Sigaba-Sigaba Sigilikɛ**: Ka sigi dɔɔni dɔɔni ka kow ye
- **Segin-kɔfɛ Boloda**: I k'a lajɛ ko i bɛ se ka yɛlɛmaniw segin ni mako bila
- **Sɛbɛnw**: Ka sɛbɛn yɔrɔw mun na i ka sigida la baara kɛra

### Nɔfɛ Minw Bɛ Se Ka Kɛ
- **Baarakɛla Baara**: Yɔrɔ dɔw bɛ se ka nɔ bila ɲɛnajɛ tile kɛcogo ma
- **Porogaramu Kɔrɔw**: Sistɛmu kɔrɔw bɛ se ka protocol kɛrɛnkɛrɛnnenw ɲini
- **Yɔrɔjan Donni**: Ka miiri kɛ nɔfɛ kan yɔrɔjamanba tigitigilen ma
- **Jagokɛ Kɛcogo**: Ka a lajɛ ko yɔrɔw t'u ka baara kunba tiɲɛ

### Lakanabaliya Danbe
- **Lakanabaliya Jɔgɔnya**: Ghost ye lakanabaliya dankun dɔ ye, a tɛ ɲɔgɔn bɛɛ ye
- **Ɲɛmɔgɔya Taamasiɲɛ**: Lakanabaliya bɛ jateminɛ ni kura mako wajibiya
- **Baarakɛlaw Dege**: Fɛɛrɛw ka kan ka jɛɲɔgɔnya ni lakanabaliya kɔlɔsili ye
- **Farati Yɛlɛmani**: Kabakoyacogo kuraw bɛ se ka lakanabaliya sisan tɛmɛ

## 🎯 Kabakoyacogo Misaliwi

Hali n'a y'a k'a ye kabakoyasira siranin minw ka kulu ma, dabali kɛrɛnkɛrɛnnen bɛ bɔ baara ɲuman ni kɔrɔbɔli na:

### WannaCry-Cogo Kabakoyaw
- **Dɔgɔya**: `Set-Ghost -SMBv1` bɛ protocol faratilen datugu
- **Miiriya**: Ka a lajɛ ko sistɛmu kɔrɔ si tɛ yen min bɛ SMBv1 ɲini

### RDP kan na Ransomware
- **Dɔgɔya**: `Set-Ghost -RDP` bɛ desktop yɔrɔjan donni datugu
- **Miiriya**: Yɔrɔjan donni fɛɛrɛ wɛrɛ bɛ se ka mako kɛ

### Sɛbɛn kan na Malware
- **Dɔgɔya**: `Set-Ghost -Macros` bɛ macro kɛcogo datugu
- **Miiriya**: A bɛ se ka nɔ bila sɛbɛn tigitigilen minw be macro ye ma

### USB Fɛ Faratinaw
- **Dɔgɔya**: `Set-Ghost -USBStorage -AutoRun` bɛ USB baarakɛcogo dabila
- **Miiriya**: A bɛ se ka nɔ bila USB minɛn baarakɛ tigitigilen ma

## 🏢 Jagokɛla Kow

### Kulu Sariya Dɛmɛ
```powershell
# Ka yɔrɔw bila baara la ni Kulu Sariya registere ye
Set-Ghost -SMBv1 -RDP -AutoRun -GroupPolicy

# Yɔrɔw bɛ baara kɛ domain bɛɛ la GP kura kɔfɛ
gpupdate /force
```

### Microsoft Intune Jɛɲɔgɔnya
```powershell
# Ka Intune sariyaw da Ghost yɔrɔw la
Set-IntuneGhost -Settings $GhostSettings -Interactive

# Sariyaw bɛ sigi yɛrɛmahɔrɔnya la minɛn ɲɛminɛnw ma

```

### Sariyasɔrɔli Kunnafoni
```powershell
# Ka lakanabaliya jateminɛ rapɔrɔ da
Get-Ghost | Export-Csv -Path "SecurityAudit-$(Get-Date -Format 'yyyy-MM-dd').csv"

# Azure lakanabaliya yɔrɔ rapɔrɔ
Get-AzureGhost | Out-File "AzureSecurityReport.txt"
```

## 📚 Fɛɛrɛ Ɲumanw

### Sigilikɛ Kɔnɔ
1. **Sisan Cogoya Sɛbɛn**: `Get-Ghost` kɛ yɛlɛmaniw kɔnɔ
2. **K'a Lajɛ Kɔnɔkɔnɔ**: Ka a jira sigida la min t'a ye baarakɛyɔrɔ ye
3. **Segin-kɔfɛ Boloda Da**: Ka a lɔn yɔrɔ o yɔrɔ segin cogo
4. **Mɔgɔw ka Lajɛli**: Ka a lajɛ ko jagokɛ kulanw b'u sɔn yɛlɛmaniw la

### Sigilikɛ Waati La
1. **Sigaba-Sigaba Fɛɛrɛ**: Ka sigi fɔlɔ kulu tilɛmuw la
2. **Nɔfɛ Filɛli**: Ka baarakɛlaw ka kabakow walima sistɛmu kow lajɛ
3. **Kow Sɛbɛn**: Ka ko o ko sɛbɛn don na la ka jira
4. **Yɛlɛmani Kunnafoni**: Ka baarakɛlaw kunnafoni lakanabaliya ɲɛtaa la

### Sigilikɛ Kɔfɛ
1. **Jateminɛ Tuma Bɛɛ**: `Get-Ghost` kɛ waati ka tɛmɛ ka yɔrɔw lajɛ
2. **Sɛbɛnw Kura**: Ka lakanabaliya labɛnniw to kura ye
3. **Baarakɛcogo Lajɛli**: Ka lakanabaliya kow jateminɛ
4. **Ɲɛtaa Taamasiɲɛ**: Ka yɔrɔw yɛlɛma k'a sɔrɔ farati yɔrɔ la

## 🔧 Ko Ɲɔgɔndan

### Ko Minw Ka Teli
- **Yamaruya Filiw**: Ka PowerShell taabolo sanfɛmɔgɔlen lajɛ
- **Baarakɛminɛn Dantigɛli**: Baarakɛminɛn dɔw bɛ se ka dantigɛ sɔrɔ
- **Porogaramu Bɛncogo**: Ka jateminɛ kɛ ni jagokɛ porogaramuw ye
- **Intirinɛti Jɛɲɔgɔnya**: Ka a lajɛ ko yɔrɔjan donni bɛ baara kɛ hali bi

### Segin Sugandiliw
```powershell
# Ka baarakɛminɛn kɛrɛnkɛrɛnnenw segin baara la ni mako bila
Set-RDP -Enable
Set-SMBv1 -Enable
Set-AutoRun -Enable
Set-Macros -Enable
```

## 👨‍💻 Sɛbɛnnikɛla Kan

**Jim Tyler** - Microsoft MVP PowerShell la
- **YouTube**: [@PowerShellEngineer](https://youtube.com/@PowerShellEngineer) (10,000+ sɔrɔbagaw)
- **Kunnafoni Bɔli**: [PowerShell.News](https://powershell.news) - Dɔgɔkun lakanabaliya kunnafoni
- **Sɛbɛnnikɛla**: "PowerShell for Systems Engineers"
- **Kɔnɔnakow**: PowerShell yɛrɛmahɔrɔnya ni Windows lakanabaliya san caman na

## 📄 Yamaruya ni Kɔfɔ

### MIT Yamaruya
Ghost dira a fɛ MIT Yamaruya jukɔrɔ ka baarakɛ kɛ bila, ka yɛlɛma ani ka tila.

### Lakanabaliya Kɔfɔ
- **Latigɛli Si Tɛ Yen**: Ghost dira a fɛ "a cogo la" latigɛli si tɛ
- **Kɔrɔbɔli Ka Kan**: Tuma bɛɛ k'a lajɛ sigida la min t'a ye baarakɛyɔrɔ ye fɔlɔ
- **Ɲɛnamayakɛlaw ka Ladon**: Baarakɛyɔrɔ sigilikɛ la, ka hakilijagabɔ kɛ ni lakanabaliya ɲɛnamayakɛlaw ye
- **Baarakɛcogo Nɔfɛ**: Sɛbɛnnikɛlaw tɛ kunfatigɛ baarakɛ dabali la
- **Lakanabaliya Bɛɛlabɛɛ**: Ghost ye lakanabaliya fɛɛrɛ kɔnɔkow dɔ ye

### Dɛmɛ
- **GitHub Kow**: [Ka bug kunnafonidi walima ka fɛɛrɛ kuraw ɲini](https://github.com/jimrtyler/Ghost/issues)
- **Sɛbɛnw**: `Get-Help <function> -Full` baara kɛ ni dɛmɛ koɲuman ma
- **Foroba**: PowerShell ni lakanabaliya foroba foro

---

**🔒 I ka lakanabaliya yɔrɔ barika ni Ghost ye - nka tuma bɛɛ k'a lajɛ fɔlɔ.**

```powershell
# Ka daminɛ ni jateminɛ ye, kana miiriya ye
Get-Ghost
```

**⭐ Ni Ghost y'i ka lakanabaliya yɔrɔ ɲɛtaa la, ka nin repository dɔlɔn di!**