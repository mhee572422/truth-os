# TRUTH OS: TECHNICAL MANUAL & ARCHITECTURE SPECIFICATION

**Version:** 1.0.0-PROD  
**Core Axiom:** $1+1=2$ (Deterministic Mathematical Foundation)  
**Repository:** `https://github.com/mhee572422/truth-os`  
**Live Gateway:** `https://btru-logic.earth`  
**Challenge:** NASA Space Apps Challenge — Earth System Trend Detective  

---

## 1. System Overview & Core Philosophy

**Truth OS** เป็นระบบปฏิบัติการเชิงกำหนด (Deterministic Operating System) แบบ Glass Box รุ่นแรกที่ออกแบบมาเพื่อแก้ไขวิกฤตความน่าเชื่อถือของข้อมูลด้านสิ่งแวดล้อมและภูมิอากาศ ระบบทั่วไปมักพึ่งพาโมเดลความน่าจะเป็นแบบกล่องดำ (Black-box Probabilistic Models) ซึ่งเสี่ยงต่อความลำเอียง ความคลาดเคลื่อนของเซ็นเซอร์ (Sensor Drift) และการดัดแปลงข้อมูลย้อนหลัง 

Truth OS จึงแทนที่ความไม่แน่นอนเหล่านี้ด้วย **สัจพจน์ทางคณิตศาสตร์ ($1+1=2$)** และ **ลายเซ็นเข้ารหัสลับ (Cryptographic Signatures)** เพื่อรับประกันความถูกต้องของข้อมูลโทรมาตร (Telemetry) ตั้งแต่ต้นทางจนถึงการแสดงผลสู่สาธารณะ

---

## 2. The 6-Layer Architecture (สถาปัตยกรรม 6 เลเยอร์)

สถาปัตยกรรมของ Truth OS ถูกแบ่งออกเป็น 6 ชั้นอิสระที่มีการตรวจสอบแบบ Zero-Trust ในทุกรอยต่อของระบบ:

```text
+-----------------------------------------------------------------+
| Layer 6: Glass Box Public Verification Dashboard                |
+-----------------------------------------------------------------+
| Layer 5: Automated Forensic & Quarantine Engine                 |
+-----------------------------------------------------------------+
| Layer 4: Immutable Block Anchoring & Signatures (Ed25519)       |
+-----------------------------------------------------------------+
| Layer 3: Zero-Trust Empirical Binding (Sentinel-2 Ground Truth) |
+-----------------------------------------------------------------+
| Layer 2: Common Data-Financial Protocol (CDFP)                  |
+-----------------------------------------------------------------+
| Layer 1: Axiomatic Core ($1+1=2$)                               |
+-----------------------------------------------------------------+
