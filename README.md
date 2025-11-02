# 🚀 SMM Panel - Social Media Marketing Platform

Platform all-in-one untuk mengelola strategi pemasaran digital bisnis Anda. Sistem SMM Panel yang terintegrasi dengan provider terpercaya untuk berbagai layanan social media marketing.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge)](https://uboosters.com)
[![API Documentation](https://img.shields.io/badge/API-Documentation-green?style=for-the-badge)](#api-documentation)

## 🌟 Live Demo

🔗 **[https://uboosters.com](https://uboosters.com)**

Platform Digital Marketing Indonesia - Solusi Profesional untuk Bisnis Online Anda

### Provider Features
- ✅ SMM Panel murah di Indonesia
- ✅ Layanan terintegrasi untuk berbagai platform sosial media
- ✅ Dashboard yang mudah digunakan
- ✅ API yang powerful dan dokumentasi lengkap
- ✅ Support pembayaran lokal Indonesia

## 📋 Fitur Utama

### 🎯 Layanan Marketing
- **Instagram**: Followers, Likes, Views, Comments, Reels
- **Facebook**: Page Likes, Followers, Post Engagement
- **Twitter/X**: Followers, Retweets, Likes
- **TikTok**: Followers, Likes, Views
- **YouTube**: Subscribers, Views, Likes
- **Telegram**: Members, Post Views
- **Dan masih banyak lagi...**

### 💼 Dashboard & Management
- User-friendly interface
- Real-time order tracking
- Order history & analytics
- Balance management
- API key management
- Multi-currency support

### 🔧 API Integration
- RESTful API (v1 & v2)
- JSON response format
- Rate limiting protection
- Secure authentication
- Comprehensive documentation
- Multiple endpoints

## 🚀 Quick Start

### Prerequisites
- PHP 7.4 atau lebih tinggi
- MySQL 5.7 atau lebih tinggi
- Web server (Apache/Nginx)
- Composer (optional)

### Installation

1. **Clone repository**
```bash
git clone https://github.com/adhe222/smm-panel.git
cd smm-panel
```

2. **Setup database**
```bash
mysql -u root -p < database.sql
```

3. **Configure environment**
```bash
cp .env.example .env
# Edit .env dengan kredensial database Anda
```

4. **Set permissions**
```bash
chmod 755 -R public/
chmod 644 .htaccess
```

5. **Access your installation**
```
http://yourdomain.com
```

## 📚 API Documentation

### Base URL
```
https://yourdomain.com/api/v1  # Standard API
https://yourdomain.com/api/v2  # Extended API
```

### Authentication
Semua request memerlukan API key yang bisa didapatkan dari dashboard Anda.

### Quick Examples

#### 1. Get Services List
```bash
curl -X POST https://yourdomain.com/api/v1 \
  -d "key=YOUR_API_KEY" \
  -d "action=services"
```

#### 2. Place Order
```bash
curl -X POST https://yourdomain.com/api/v1 \
  -d "key=YOUR_API_KEY" \
  -d "action=add" \
  -d "service=1" \
  -d "link=https://instagram.com/username" \
  -d "quantity=1000"
```

#### 3. Check Order Status
```bash
curl -X POST https://yourdomain.com/api/v1 \
  -d "key=YOUR_API_KEY" \
  -d "action=status" \
  -d "order=12345"
```

#### 4. Get Balance
```bash
curl -X POST https://yourdomain.com/api/v1 \
  -d "key=YOUR_API_KEY" \
  -d "action=balance"
```

### Response Format

**Success:**
```json
{
  "status": "success",
  "order": "12345"
}
```

**Error:**
```json
{
  "error": "Not enough funds on balance"
}
```

## 🛠️ Tech Stack

- **Backend**: PHP 7.4+
- **Database**: MySQL 5.7+
- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 4
- **API**: RESTful JSON API
- **Security**: SQL Injection Protection, XSS Protection, CSRF Tokens

## 📱 Features Breakdown

### User Features
- ✅ Registration & Login system
- ✅ Email verification
- ✅ Password recovery
- ✅ Multi-language support
- ✅ Responsive design
- ✅ Order management
- ✅ Transaction history
- ✅ API access

### Admin Features
- ✅ User management
- ✅ Service management
- ✅ Order management
- ✅ Payment gateway integration
- ✅ Settings & configuration
- ✅ Reports & analytics
- ✅ API monitoring

### API Features (v2)
- ✅ User information endpoint
- ✅ Orders history with pagination
- ✅ Refill request
- ✅ Cancel order
- ✅ Extended service details

## 🔒 Security

- SQL Injection protection dengan prepared statements
- XSS protection
- CSRF token validation
- Rate limiting untuk API
- Secure password hashing (bcrypt)
- HTTPS enforcement
- API key authentication

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📞 Support

Untuk bantuan teknis atau pertanyaan:

- 🌐 Website: [https://uboosters.com](https://uboosters.com)
- 📧 Email: support@uboosters.com
- 💬 Live Chat: Available on website

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Provider: [UBOOSTERS](https://uboosters.com) - SMM Panel murah di Indonesia
- Thanks to all contributors
- Inspired by modern SMM panel systems

## 📊 Stats

- ⚡ Fast API response time (<200ms)
- 🔐 Secure & encrypted transactions
- 📈 99.9% uptime guarantee
- 🌍 International service coverage
- 💳 Multiple payment methods
