# 문태성 / TAESEONG MOON

`RTL DESIGN` · `DESIGN VERIFICATION` · `FPGA`

Verilog/SystemVerilog 기반 RTL 설계 및 검증 엔지니어를 목표로 하고 있습니다.  
반도체 IP 검증 실무와 Bus·Protocol RTL 설계, UVM 및 FPGA 검증 경험이 있습니다.

---

## Career

`2023.11 — 2025.05`

- Automotive BIST / Pixel Shift IP 검증
- RTL Spec 분석 및 Verilog Testbench 작성
- Simulation 및 FPGA 기반 검증

---

## Technical Skills

| Category | Skills |
|:---|:---|
| HDL | Verilog, SystemVerilog |
| Verification | UVM, Testbench, Simulation |
| Bus / Protocol | AMBA APB, I2C, SPI, UART |
| Programming | C, Python |
| EDA Tools | Vivado, Vitis, VCS, Xcelium, Verdi |
| Environment | Linux, Vim |

---

## Education

| 기간 | 교육기관 | 과정 |
|:---:|:---|:---|
| 2026.01 ~ 현재 | 서울기술교육센터 | 온디바이스 AI 시스템반도체 설계 과정 1기 |
| 2023.06 ~ 2023.09 | ETRI SW-SoC 융합 아카데미 | 디지털 RTL 회로설계 전문가 과정 |

---

## Projects

> 온디바이스 AI 시스템반도체 설계 과정에서 수행한 프로젝트입니다.

### 01. I2C & SPI RTL Design

`Verilog` `SystemVerilog` `UVM` `VCS` `Verdi` `Basys3`

I2C 및 SPI Master/Slave를 RTL로 설계하고  
Simulation, UVM 및 두 FPGA 간 통신을 통해 동작을 검증했습니다.

- I2C Read/Write 및 Multi-byte Write 구현
- SPI Mode 0~3 Master 및 Mode 0 Slave 구현
- Random Sequence 기반 Scoreboard 검증
- Functional Coverage 측정
- 두 Basys3 Board 간 I2C/SPI 통신 검증

[Repository →](https://github.com/taeseong-dev/i2c-spi-rtl-design)

---

### 02. APB Bus & Peripheral Design

`Verilog` `SystemVerilog` `UVM` `AMBA APB` `VCS` `Verdi` `Basys3`

APB Bus와 Memory-Mapped Peripheral을 RTL로 설계하고
Simulation, UVM 및 FPGA를 통해 동작을 검증했습니다.

- APB Master 및 Address Decoder 설계
- BRAM, GPIO, UART, FND Peripheral 구현
- RV32I CPU와 APB Peripheral 연동
- SystemVerilog/UVM 기반 APB 및 Peripheral 검증
- Basys3 FPGA 동작 검증

[Repository →](https://github.com/taeseong-dev/apb-bus-peripherals)

---

### 03. OV7670·VGA Rhythm Game

`Verilog` `SystemVerilog` `OV7670` `VGA` `UART` `Basys3`

OV7670 영상 입력과 VGA 출력을 활용한  
4-Lane 리듬게임 팀 프로젝트입니다.

- PC로부터 Note Data를 수신하는 UART RX 설계
- 수신 Data 기반 Note 위치 제어 로직 구현
- Simulation 및 FPGA 동작 검증

[Repository →](https://github.com/taeseong-dev/vga_rhythm_game)

---

### 04. RISC-V RV32I CPU Design

`Verilog` `RISC-V` `RV32I` `Single-Cycle` `Multi-Cycle` `Vivado`

RV32I 기본 명령어 37개를 지원하는 Single-Cycle CPU를 설계하고,  
명령어 실행 단계를 분리한 FSM 기반 Multi-Cycle 구조로 확장했습니다.

- Instruction Type별 Datapath 및 Control Logic 설계
- Byte, Halfword 및 Word 단위 Load/Store 구현
- `FETCH`, `DECODE`, `EXECUTE`, `MEM`, `WB` 기반 Multi-Cycle FSM 설계
- ALU 연산, Memory Access, Branch·Jump 및 State 전환 Simulation 검증

[Repository →](https://github.com/taeseong-dev/riscv-rv32i-cpu)
