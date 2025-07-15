# Week 5 Summary

## 📊 Week Overview
- **Week**: 5/8
- **Period**: 09/06/2025 - 15/06/2025
- **Total Days**: 7
- **Total Hours**: 40

## 🎯 Week Achievements
- Hiểu cách xây dựng hệ thống giám sát và quản lý tài nguyên AWS một cách tự động, hiệu quả. Tự động hóa quy trình vận hành như tắt server không sử dụng và gửi cảnh báo qua Slack. 
- Triển khai thành công hệ thống giám sát bằng CloudWatch kết hợp với Grafana để trực quan hóa dữ liệu. Quản lý quyền truy cập EC2 theo Tag, tăng tính bảo mật và kiểm soát. 
- Áp dụng AWS Systems Manager để chạy lệnh hàng loạt và cập nhật hệ thống từ xa mà không cần SSH.

## 🔧 AWS Services Learned
- **Amazon Lambda**
- **AWS CloudWatch**
- **AWS Systems Manager (SSM)**

## 📚 Key Skills Developed
- Viết hàm Lambda để xử lý các sự kiện tự động như shutdown EC2 và gửi cảnh báo. 
- Thiết lập và cấu hình CloudWatch Alarm, Log Group và Metric Filter. 
- Kết nối CloudWatch với Grafana để trực quan hóa trạng thái hệ thống theo thời gian thực. 
- Gán và sử dụng Tag để tạo điều kiện kiểm soát truy cập theo nguyên tắc least privilege. 
- Thực hành sử dụng Run Command, Patch Manager, và Automation trong SSM để quản lý tập trung nhiều EC2

## 💡 Technical Highlights

### Core Learning Areas
- Monitoring System với CloudWatch & Grafana
- Automation với AWS Lambda
- Resource Management bằng Tag + IAM
- Remote Operations với AWS Systems Manager

### Hands-on Experience
- Tạo và cấu hình CloudWatch Alarm, Log Group, Metric Filter
- Viết hàm Lambda để tự động tắt EC2 và gửi cảnh báo
- Gắn Tag cho EC2 và phân quyền truy cập thông qua IAM policy
- Sử dụng Run Command, Patch Manager, và Automation trong SSM để quản lý EC2 từ xa

### Best Practices Applied
- Nguyên tắc least privilege trong IAM
- Tự động hóa giám sát và cảnh báo sự cố
- Logging & Observability chuẩn hóa qua CloudWatch Logs
- Quản lý tập trung EC2 không cần SSH bằng Systems Manager

## 🚧 Challenges & Solutions

### Major Challenges
- Tích hợp dữ liệu CloudWatch vào Grafana
- Viết IAM policy đúng cú pháp và đủ điều kiện kiểm soát bằng Tag

### Solutions Implemented
- Debug quyền truy cập cho IAM role Grafana, sử dụng CloudWatchReadOnlyAccess
- Áp dụng điều kiện aws:ResourceTag đúng cách trong IAM policy

### Lessons Learned
- IAM policy viết sai nhỏ cũng có thể làm toàn bộ fail
- CloudWatch + Grafana là công cụ mạnh để trực quan hóa hệ thống

## 💭 Week Reflection

### What Went Well
- Tích hợp thành công hệ thống giám sát real-time với CloudWatch và Grafana
- Viết Lambda để tự động hóa cảnh báo và shutdown server
- Quản lý truy cập EC2 hiệu quả với IAM + Tag

### Areas for Improvement
- Cần nắm vững hơn về điều kiện trong IAM policy (Condition block)
- Thời gian debug khi kết nối Grafana còn hơi lâu

### Key Insights
- Tự động hóa vận hành giúp tiết kiệm rất nhiều thời gian và giảm lỗi người
- Kết nối dịch vụ AWS cần đảm bảo quyền truy cập chính xác

## 📋 Next Week Planning

### Focus Areas
- Cleck integrated in Nodejs Application
- Project implementation
- Making idea for AWS Final Workshop
- Third-party integration

### Learning Objectives
- Integrate authentication, library services
- Complete project features
- Develop APIs
- Master service integration

### Preparation Tasks
- Study Clerk library
- Plan service integration to final workshop
- Try my best to develop a completed nodejs app before integrated AWS services phase.

## 📊 Week Assessment

### Technical Progress
- **Score**: 6/10
- **Highlights**: Triển khai hệ thống giám sát và tự động hóa EC2
- **Growth Areas**: Viết policy IAM nâng cao, tối ưu hóa Lambda

### Practical Application
- **Score**: 8/10
- **Achievements**: Tạo hệ thống giám sát trực quan và quản lý từ xa
- **Next Steps**: Hoàn thiện hệ thống cảnh báo và logging đầy đủ

### Overall Satisfaction
- **Score**: 6/10
- **Week Summary**: Học được nhiều công cụ mạnh của AWS giúp quản lý hệ thống hiệu quả hơn
- **Momentum**: Cảm thấy tự tin hơn trong việc thiết kế hệ thống cloud tự động hóa

## 📎 Evidence & Documentation

### Completed Labs
- ✅ Lab: Tạo hệ thống giám sát với CloudWatch + Grafana
- ✅ Lab: Quản lý EC2 với Tag + IAM
- ✅ Lab: Sử dụng AWS Systems Manager để điều khiển EC2 từ xa
- ✅ Lambda Function để tự động tắt server và gửi thông báo

### Project Progress
- ❌ Chưa tiến hành: dự kiến sẽ tiến hành vào tuần kế tiếp

### Learning Resources
- [Automated server shutdown and Slack messaging with AWS Lambda](https://docs.google.com/document/d/1cXD6cLuAi6cqub-j-CGB_UkAlNg_WB-7/edit?usp=drive_link&ouid=105474698965297962990&rtpof=true&sd=true)
- [Create System Monitor with Amazon Cloudwatch and Grafana](https://docs.google.com/document/d/1Idt0uw-MqbZAe6tzWg_NuJMwIHK-wyon/edit?usp=drive_link&ouid=105474698965297962990&rtpof=true&sd=true)

---

**📝 Week 5 Summary**  
*Period: 09/06/2025 - 15/06/2025*  
*Total Learning Hours: 40*  
*Progress Status: On Track ✅*

---
*Weekly Summary by: Nguyễn Đan*  
*Review Date: 15/06/2025*
