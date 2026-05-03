# my_jlcpcb_lib_for_kicad

KiCAD component library converted from LCSC/JLCPCB using two tools: [easyeda2kicad](https://github.com/uPesy/easyeda2kicad.py) and [JLC2KiCad_lib](https://github.com/TousstNicolas/JLC2KiCad_lib).

## Setup

```bash
cd /home/ubuntu/kicad_lcsc
source ~/.venv/eda/bin/activate
```

## Usage

**easyeda2kicad**
```bash
easyeda2kicad --full --lcsc_id=C165948 --output ~/jlc_lib/my_lib --overwrite
```

**JLC2KiCad_lib**
```bash
JLC2KiCadLib C165948 -dir ./jlc_lib -model_dir 3d_models -footprint_lib TYPE-C-31-M-12.pretty -symbol_lib_dir symbols -symbol_lib TYPE-C-31-M-12
```

Replace `C165948` with the LCSC part number of the component you want to convert.

## Components

| Name | LCSC ID | Symbol | Footprint |
|------|---------|--------|-----------|
| [KANGNEX WJ2EDGR-5.08-02P](https://www.lcsc.com/product-detail/C8383.html) | C8383 | CustomTerminalBlock:CONN-TH_WJ2EDGR-5.08-2P | CustomTerminalBlock:CONN-TH_WJ2EDGR-5.08-2P |
| [KANGNEX WJ2EDGK-5.08-02P](https://www.lcsc.com/product-detail/C71370.html) | C71370 | CustomTerminalBlock:CONN-TH_WJ2EDGR-5.08-2P | CustomTerminalBlock:CONN-TH_WJ2EDGR-5.08-2P |
| [KANGNEX WJ2EDGR-5.08-03P](https://www.lcsc.com/product-detail/C70914.html) | C70914 | CustomTerminalBlock:CONN-TH_3P-P5.08_WJ2EDGR-5.08-3P | CustomTerminalBlock:CONN-TH_3P-P5.08_WJ2EDGR-5.08-3P |
| [KANGNEX WJ2EDGK-5.08-03P](https://www.lcsc.com/product-detail/C71371.html) | C71371 | CustomTerminalBlock:CONN-TH_3P-P5.08_WJ2EDGR-5.08-3P | CustomTerminalBlock:CONN-TH_3P-P5.08_WJ2EDGR-5.08-3P |
| [KANGNEX WJ2EDGR-5.08-04P](https://www.lcsc.com/product-detail/C8443.html) | C8443 | CustomTerminalBlock:CONN-TH_4P-P5.08_WJ2EDGR-5.08-4P | CustomTerminalBlock:CONN-TH_4P-P5.08_WJ2EDGR-5.08-4P |
| [KANGNEX WJ2EDGK-5.08-04P](https://www.lcsc.com/product-detail/C71372.html) | C71372 | CustomTerminalBlock:CONN-TH_4P-P5.08_WJ2EDGR-5.08-4P | CustomTerminalBlock:CONN-TH_4P-P5.08_WJ2EDGR-5.08-4P |
| [RJ45 Ethernet Connector](https://www.lcsc.com/product-detail/C386757.html) | C386757 | CustomEthernetConnector:RJ45-TH_R-RJ45R08P-C000 | CustomEthernetConnector:RJ45-TH_R-RJ45R08P-C000 |
| [onsemi ESD5Z3.3T1G TVS](https://www.lcsc.com/product-detail/C61148.html) | C61148 | CustomUncategorized:ESD5Z3_3T1G_0 | CustomUncategorized:SOD-523F_L1.2-W0.8-LS1.7-RD |
---
