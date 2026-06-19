# Chính Sách Quyền Riêng Tư — Ứng Dụng Tinventor

**Cập nhật lần cuối:** 19/06/2026

TINVENTOR ELECTRONICS ("chúng tôi") phát triển ứng dụng **Tinventor** ("Ứng dụng")
dùng để kết nối và điều khiển các thiết bị phần cứng BDK (công tắc/relay thông minh).
Chính sách này giải thích cách Ứng dụng xử lý thông tin của bạn.

Tôn chỉ của chúng tôi: **Ứng dụng lưu trữ dữ liệu chủ yếu trên thiết bị của bạn và
không thu thập, không bán thông tin cá nhân cho bên thứ ba.**


## 1. Thông tin Ứng dụng xử lý

### 1.1. Vị trí (Location)
- Ứng dụng yêu cầu quyền truy cập vị trí **chỉ khi đang sử dụng** (When In Use).
- Mục đích **duy nhất**: hệ điều hành iOS/Android bắt buộc phải có quyền vị trí thì
  Ứng dụng mới đọc được **tên mạng WiFi (SSID)** hiện tại, nhằm xác minh bạn đang kết
  nối đúng mạng của thiết bị.
- Chúng tôi **không** thu thập, **không** lưu trữ và **không** truyền tọa độ GPS của
  bạn đi bất kỳ đâu.

### 1.2. Mạng nội bộ (Local Network)
- Ứng dụng dùng quyền truy cập mạng nội bộ để tìm thiết bị BDK trong cùng mạng WiFi
  (qua giao thức UDP).
- Việc này chỉ diễn ra **trong mạng nội bộ của bạn**, dữ liệu không được gửi ra Internet.

### 1.3. Camera
- Ứng dụng dùng camera **chỉ để quét mã QR** phục vụ việc thêm/chia sẻ thiết bị.
- Hình ảnh từ camera được xử lý ngay trên thiết bị và **không được lưu hay gửi đi**.

### 1.4. Thông tin thiết bị & cấu hình
- Ứng dụng lưu trên máy của bạn: tên gợi nhớ thiết bị, mã thiết bị, tên kênh tùy chỉnh,
  địa chỉ IP/MQTT gần nhất.
- Khi bạn cấu hình WiFi cho thiết bị, **tên WiFi và mật khẩu** được gửi tới thiết bị
  phần cứng của bạn để thiết bị kết nối Internet. Ở chế độ "Online", lệnh này đi qua
  máy chủ trung gian (MQTT broker) của chúng tôi để đến thiết bị.
- Các dữ liệu này được dùng **chỉ để vận hành chức năng của Ứng dụng**.


## 2. Lưu trữ dữ liệu

- Phần lớn dữ liệu được lưu **cục bộ trên thiết bị của bạn** (bộ nhớ ứng dụng) và sẽ bị
  xóa khi bạn gỡ cài đặt Ứng dụng.
- Chúng tôi **không** vận hành cơ sở dữ liệu hồ sơ người dùng và **không** thu thập dữ
  liệu cá nhân để phân tích hành vi.


## 3. Chia sẻ dữ liệu

- Chúng tôi **không bán, không cho thuê, không chia sẻ** thông tin của bạn cho bên thứ
  ba vì mục đích quảng cáo hay tiếp thị.
- Ứng dụng **không** tích hợp công cụ phân tích (analytics), quảng cáo, hay theo dõi
  (tracking) của bên thứ ba.


## 4. Bảo mật

- Chúng tôi áp dụng các biện pháp hợp lý để bảo vệ dữ liệu.
- Lưu ý: dữ liệu truyền tới thiết bị trong mạng nội bộ (UDP) và qua máy chủ trung gian
  (MQTT) phục vụ mục đích điều khiển thiết bị. Bạn nên sử dụng Ứng dụng trên mạng WiFi
  tin cậy.


## 5. Quyền riêng tư của trẻ em

Ứng dụng không hướng đến trẻ em dưới 13 tuổi và không cố ý thu thập dữ liệu từ trẻ em.


## 6. Thay đổi chính sách

Chúng tôi có thể cập nhật chính sách này theo thời gian. Phiên bản mới sẽ được đăng tại
trang này kèm ngày cập nhật.


## 7. Liên hệ

Nếu bạn có câu hỏi về chính sách quyền riêng tư này, vui lòng liên hệ:

- **Đơn vị:** TINVENTOR ELECTRONICS
- **Email:** info@tinventor.vn
- **Website:** https://tinventor.vn



# Privacy Policy — Tinventor App (English)

**Last updated:** June 19, 2026

TINVENTOR ELECTRONICS ("we", "us") develops the **Tinventor** application
("the App"), used to connect and control BDK smart switch/relay hardware devices.
This policy explains how the App handles your information.

Our principle: **The App stores data primarily on your device and does not collect or
sell personal information to third parties.**

## 1. Information the App Processes

**1.1. Location** — The App requests location access **only while in use**. Its sole
purpose is that iOS/Android require location permission to read the current **WiFi
network name (SSID)**, in order to verify you are connected to the correct device
network. We do **not** collect, store, or transmit your GPS coordinates.

**1.2. Local Network** — The App uses local network access to discover BDK devices on
the same WiFi network (via UDP). This happens **within your local network only**; data
is not sent to the Internet.

**1.3. Camera** — The App uses the camera **only to scan QR codes** for adding/sharing
devices. Camera images are processed on-device and are **never stored or transmitted**.

**1.4. Device Information & Configuration** — The App stores on your device: device
nicknames, device IDs, custom channel names, last known IP/MQTT address. When you
configure WiFi for a device, the **WiFi name and password** are sent to your hardware
device so it can connect to the Internet. In "Online" mode, this command passes through
our intermediary server (MQTT broker) to reach the device. This data is used **solely to
operate the App's functionality**.

## 2. Data Storage
Most data is stored **locally on your device** and is removed when you uninstall the App.
We do **not** operate a user profile database and do **not** collect personal data for
behavioral analytics.

## 3. Data Sharing
We do **not** sell, rent, or share your information with third parties for advertising or
marketing. The App integrates **no** third-party analytics, advertising, or tracking
tools.

## 4. Security
We apply reasonable measures to protect data. Note that data transmitted to devices on
the local network (UDP) and via the intermediary server (MQTT) serves device-control
purposes. Please use the App on a trusted WiFi network.

## 5. Children's Privacy
The App is not directed at children under 13 and does not knowingly collect data from
children.

## 6. Changes to This Policy
We may update this policy over time. The latest version will be posted on this page with
its update date.

## 7. Contact
- **Entity:** TINVENTOR ELECTRONICS
- **Email:** info@tinventor.vn
- **Website:** https://tinventor.vn
