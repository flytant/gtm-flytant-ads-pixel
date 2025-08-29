# Flytant Ads Pixel

A Google Tag Manager template for tracking events with the Flytant Ads platform.

![Flytant Ads](https://img.shields.io/badge/Flytant-Ads%20Pixel-blue)
![GTM Template](https://img.shields.io/badge/GTM-Template-green)
![Version](https://img.shields.io/badge/version-1.0.0-orange)

## 🚀 Features

- ✅ **Simple Setup**: Easy-to-use GTM template interface
- ✅ **Custom Events**: Track page views, purchases, signups, and custom events
- ✅ **Flexible Parameters**: Send additional data with each event
- ✅ **Debug Support**: Built-in logging for troubleshooting
- ✅ **Lightweight**: Minimal performance impact

## 📦 Quick Installation

### Method 1: From GTM Gallery (Recommended)
1. Open Google Tag Manager
2. Go to Templates > Tag Templates
3. Click "Search Gallery" 
4. Search for "Flytant Ads Pixel"
5. Click "Add to Workspace"

### Method 2: Manual Import
1. Download `template.tpl` from this repository
2. In GTM: Templates > Tag Templates > Import
3. Upload the template file
4. Save to your workspace

## ⚙️ Configuration

### Required Fields
- **Event Name**: Type of event (page_view, purchase, lead, etc.)
- **Page URL**: Where event occurred (use `{{Page URL}}` variable)

### Optional Fields
- **Additional Parameters**: Custom key-value data for enhanced tracking

## 📋 Usage Examples

### Basic Page View Tracking
