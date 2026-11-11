# Awesome react native with stars

<br/>

<p align="center">
    <img alt="awesome react native" src="arn.svg" width="480" />
</p>

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img src="https://awesome.re/badge.svg" alt="Awesome" /></a>
</p>

Awesome React Native is a curated list of the best libraries, tools, and learning resources for building React Native apps today. Every entry is checked for maintenance and relevance — if it's here, it works with modern React Native. PRs are welcome, see [contributing](CONTRIBUTING.md).

## Contents

* [Getting Started](#getting-started)
* [AI-Assisted Development](#ai-assisted-development)
  * [Agents & Skills](#agents--skills)
  * [MCP Servers](#mcp-servers)
  * [On-Device AI](#on-device-ai)
  * [AI App Builders](#ai-app-builders)
* [Components](#components)
  * [UI](#ui)
  * [Lists](#lists)
  * [Navigation](#navigation)
  * [Sheets, Menus & Toasts](#sheets-menus--toasts)
  * [Forms & Keyboard](#forms--keyboard)
  * [Text & Rich Content](#text--rich-content)
  * [Image & Camera](#image--camera)
  * [Video & Audio](#video--audio)
  * [Maps & Location](#maps--location)
  * [Charts](#charts)
  * [Animation & Gestures](#animation--gestures)
  * [Styling & Design Systems](#styling--design-systems)
  * [Internationalization](#internationalization)
  * [System & Device](#system--device)
  * [Notifications](#notifications)
  * [Web & WebViews](#web--webviews)
  * [Other Platforms](#other-platforms)
* [Data](#data)
  * [State Management](#state-management)
  * [Storage & Databases](#storage--databases)
  * [Networking](#networking)
* [Services & Integrations](#services--integrations)
* [Payments & Monetization](#payments--monetization)
* [Development Tools](#development-tools)
  * [Tooling & IDE](#tooling--ide)
  * [Debugging](#debugging)
  * [Testing](#testing)
  * [Builds, Deployment & OTA Updates](#builds-deployment--ota-updates)
  * [Building Libraries](#building-libraries)
* [Starters & Boilerplates](#starters--boilerplates)
* [Open Source Apps](#open-source-apps)
* [Learning](#learning)
* [Staying Up to Date](#staying-up-to-date)

## Getting Started

* [Upgrade Helper](https://github.com/react-native-community/upgrade-helper) ⭐ 4,073 | 🐛 16 | 🌐 TypeScript | 📅 2026-07-23 - Web tool that shows the exact diff between two React Native versions for painless upgrades.
* [Expo Examples](https://github.com/expo/examples) ⭐ 3,753 | 🐛 136 | 🌐 TypeScript | 📅 2026-10-30 - Example projects demonstrating Expo APIs and integrations.
* [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge) ⭐ 1,318 | 🐛 3 | 🌐 Shell | 📅 2026-11-10 - The raw version-to-version diffs powering Upgrade Helper.
* [React Native](https://reactnative.dev) - Official documentation, including environment setup, guides, and API reference.
* [Expo](https://expo.dev) - The recommended framework for building React Native apps: file-based routing, native modules, builds, and updates out of the box.
* [React Native Directory](https://reactnative.directory) - Searchable, filterable directory of React Native libraries with maintenance and New Architecture compatibility signals.

## AI-Assisted Development

Tools for building React Native apps with AI agents, and for putting AI inside your apps.

### Agents & Skills

* [Agent Skills](https://github.com/anthropics/skills) ⭐ 192,642 | 🐛 1,516 | 🌐 Python | 📅 2026-11-06 - Anthropic's public repository of agent skills, usable with Claude Code and other agents.
* [Expo Skills](https://github.com/expo/skills) ⭐ 4,111 | 🐛 107 | 🌐 Shell | 📅 2026-11-06 - Agent skills that give coding agents Expo-specific knowledge and best practices.
* [Expo AI Agents Guide](https://docs.expo.dev/agents/) - Expo's official documentation for AI-native development: agent setup, llms.txt, and best practices.
* [Claude Code + Expo](https://docs.expo.dev/agents/claude/) - Official guide for building, debugging, and deploying Expo apps with Claude Code.

### MCP Servers

* [mobile-mcp](https://github.com/mobile-next/mobile-mcp) ⭐ 10,484 | 🐛 67 | 🌐 TypeScript | 📅 2026-11-07 - MCP server for mobile automation on iOS, Android, emulators, simulators, and real devices.
* [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) ⭐ 2,216 | 🐛 24 | 🌐 TypeScript | 📅 2026-11-10 - MCP server for driving the iOS simulator: interact with UI, take screenshots, inspect the view hierarchy.
* [Expo MCP](https://docs.expo.dev/mcp/) - Expo-hosted MCP server: EAS logs, documentation search, and deployment workflows from any MCP-capable agent.
* [Maestro](https://maestro.dev) - E2E testing framework with a built-in MCP server, letting agents run flows and control devices.

### On-Device AI

* [AI SDK](https://github.com/vercel/ai) ⭐ 27,862 | 🐛 1,556 | 🌐 TypeScript | 📅 2026-11-11 - The AI toolkit for TypeScript; works in Expo and React Native apps for chat, streaming, and tool use.
* [react-native-executorch](https://github.com/software-mansion/react-native-executorch) ⭐ 1,788 | 🐛 51 | 🌐 TypeScript | 📅 2026-11-10 - Declarative on-device AI inference powered by ExecuTorch, from Software Mansion.
* [react-native-fast-tflite](https://github.com/mrousavy/react-native-fast-tflite) ⭐ 1,243 | 🐛 48 | 🌐 TypeScript | 📅 2026-09-11 - High-performance TensorFlow Lite inference with GPU acceleration.
* [llama.rn](https://github.com/mybigday/llama.rn) ⭐ 1,072 | 🐛 20 | 🌐 C | 📅 2026-11-11 - React Native binding of llama.cpp for running LLMs on device.

### AI App Builders

* [a0.dev](https://a0.dev) - Generates complete React Native apps from a prompt and ships them to the app stores.
* [Rork](https://rork.com) - AI app builder that generates Expo/React Native projects compiling to native iOS, Android, and web.

## Components

### UI

* [React Native Elements](https://github.com/react-native-elements/react-native-elements) ⭐ 25,876 | 🐛 160 | 🌐 MDX | 📅 2026-05-21 - Cross-platform UI toolkit with themed, composable components.
* [NativeBase](https://github.com/GeekyAnts/NativeBase) ⭐ 20,368 | 🐛 377 | 🌐 TypeScript | 📅 2026-01-31 - Mobile-first, accessible component library for React Native and web.
* [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) ⭐ 17,930 | 🐛 14 | 🌐 TypeScript | 📅 2026-10-19 - Customizable icon sets with support for styling and image sources.
* [lottie-react-native](https://github.com/lottie-react-native/lottie-react-native) ⭐ 17,214 | 🐛 23 | 🌐 TypeScript | 📅 2026-11-04 - Render After Effects animations natively.
* [react-native-paper](https://github.com/callstack/react-native-paper) ⭐ 14,501 | 🐛 454 | 🌐 TypeScript | 📅 2026-11-10 - Material Design components for Android and iOS.
* [Tamagui](https://github.com/tamagui/tamagui) ⭐ 14,306 | 🐛 86 | 🌐 TypeScript | 📅 2026-11-11 - Universal UI kit and style system with an optimizing compiler, 100% parity between React Native and web.
* [react-native-ui-kitten](https://github.com/akveo/react-native-ui-kitten) ⭐ 10,665 | 🐛 16 | 🌐 TypeScript | 📅 2026-10-06 - UI library based on the Eva Design System with theming support.
* [react-native-calendars](https://github.com/wix/react-native-calendars) ⭐ 10,325 | 🐛 141 | 🌐 TypeScript | 📅 2026-10-17 - Feature-rich calendar components.
* [react-native-svg](https://github.com/software-mansion/react-native-svg) ⭐ 8,013 | 🐛 275 | 🌐 TypeScript | 📅 2026-11-10 - SVG rendering for React Native and web.
* [react-native-modal](https://github.com/react-native-modal/react-native-modal) ⭐ 5,649 | 🐛 100 | 🌐 TypeScript | 📅 2026-01-29 - Enhanced, animated, customizable modal.
* [gluestack-ui](https://github.com/gluestack/gluestack-ui) ⭐ 5,356 | 🐛 20 | 🌐 TypeScript | 📅 2026-09-02 - Copy-paste components and patterns built on Tailwind-style utility classes.
* [Shoutem UI](https://github.com/shoutem/ui) ⭐ 4,984 | 🐛 104 | 🌐 JavaScript | 📅 2026-11-06 - Customizable set of styled components for React Native.
* [react-native-blur](https://github.com/margelo/react-native-blur) ⭐ 3,879 | 🐛 250 | 🌐 TypeScript | 📅 2026-05-09 - Native blur view component.
* [react-native-reanimated-carousel](https://github.com/dohooo/react-native-reanimated-carousel) ⭐ 3,437 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Swiper/carousel built entirely on Reanimated, the successor to snap-carousel.
* [react-native-pager-view](https://github.com/callstack/react-native-pager-view) ⭐ 3,372 | 🐛 84 | 🌐 TypeScript | 📅 2026-11-09 - Native ViewPager and UIPageViewController wrapper.
* [react-native-date-picker](https://github.com/henninghall/react-native-date-picker) ⭐ 2,508 | 🐛 85 | 🌐 Java | 📅 2025-06-05 - Native date and time picker for Android and iOS.
* [react-native-copilot](https://github.com/mohebifar/react-native-copilot) ⭐ 2,429 | 🐛 124 | 🌐 TypeScript | 📅 2024-12-17 - Step-by-step walkthrough tooltips for onboarding.
* [react-native-circular-progress](https://github.com/bartgryszko/react-native-circular-progress) ⭐ 2,246 | 🐛 74 | 🌐 JavaScript | 📅 2025-08-13 - Animated circular progress indicators.
* [react-native-blurhash](https://github.com/mrousavy/react-native-blurhash) ⭐ 2,242 | 🐛 33 | 🌐 Kotlin | 📅 2026-03-19 - Colorful blurry placeholders while content loads.
* [react-native-svg-transformer](https://github.com/kristerkari/react-native-svg-transformer) ⭐ 1,739 | 🐛 94 | 🌐 JavaScript | 📅 2026-10-16 - Import SVG files as components, like on the web.
* [react-native-super-grid](https://github.com/saleel/react-native-super-grid) ⭐ 1,482 | 🐛 12 | 🌐 JavaScript | 📅 2025-11-26 - Responsive grid view.
* [react-native-confirmation-code-field](https://github.com/retyui/react-native-confirmation-code-field) ⭐ 1,229 | 🐛 5 | 🌐 TypeScript | 📅 2026-11-10 - OTP/confirmation code input for iOS, Android, and web.
* [react-native-qrcode-svg](https://github.com/Expensify/react-native-qrcode-svg) ⭐ 1,176 | 🐛 59 | 🌐 JavaScript | 📅 2026-11-06 - QR code generator based on react-native-svg.
* [react-native-country-picker-modal](https://github.com/xcarpentier/react-native-country-picker-modal) ⭐ 1,112 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-01 - Country picker with flags, search, and localization.
* [react-native-hole-view](https://github.com/ibitcy/react-native-hole-view) ⭐ 446 | 🐛 7 | 🌐 TypeScript | 📅 2026-01-19 - Cut touch-through holes anywhere, perfect for onboarding highlights.
* [react-native-progress-steps](https://github.com/colbymillerdev/react-native-progress-steps) ⭐ 394 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-08 - Customizable progress stepper.

### Lists

* [FlashList](https://github.com/Shopify/flash-list) ⭐ 7,247 | 🐛 238 | 🌐 TypeScript | 📅 2026-10-01 - Shopify's fast and performant list, a drop-in replacement for FlatList.
* [recyclerlistview](https://github.com/Flipkart/recyclerlistview) ⭐ 5,428 | 🐛 266 | 🌐 TypeScript | 📅 2025-03-16 - The recycling listview that pioneered high-performance lists in React Native.
* [Legend List](https://github.com/LegendApp/legend-list) ⭐ 3,440 | 🐛 135 | 🌐 TypeScript | 📅 2026-11-07 - High-performance list in pure JS, built for the New Architecture.

### Navigation

* [React Navigation](https://github.com/react-navigation/react-navigation) ⭐ 24,524 | 🐛 325 | 🌐 TypeScript | 📅 2026-11-10 - The standard routing and navigation library for React Native.
* [react-native-navigation](https://github.com/wix/react-native-navigation) ⭐ 13,169 | 🐛 60 | 🌐 MDX | 📅 2026-11-03 - Wix's fully native navigation solution.
* [react-native-screens](https://github.com/software-mansion/react-native-screens) ⭐ 3,750 | 🐛 409 | 🌐 TypeScript | 📅 2026-11-10 - Native navigation primitives that back React Navigation's native stack.
* [react-native-bottom-tabs](https://github.com/callstack/react-native-bottom-tabs) ⭐ 1,473 | 🐛 39 | 🌐 TypeScript | 📅 2026-11-10 - Truly native bottom tab bars (SwiftUI and Material) for React Native.
* [Expo Router](https://docs.expo.dev/router/introduction/) - File-based routing for universal React Native apps, built on React Navigation.

### Sheets, Menus & Toasts

* [react-native-bottom-sheet](https://github.com/gorhom/react-native-bottom-sheet) ⭐ 9,112 | 🐛 71 | 🌐 TypeScript | 📅 2026-05-09 - Performant, interactive bottom sheet with configurable gestures.
* [Zeego](https://github.com/nandorojo/zeego) ⭐ 2,255 | 🐛 49 | 🌐 TypeScript | 📅 2026-01-28 - Menus for React Native done right — truly native dropdown and context menus.
* [react-native-actions-sheet](https://github.com/ammarahm-ed/react-native-actions-sheet) ⭐ 2,201 | 🐛 49 | 🌐 TypeScript | 📅 2026-11-01 - Cross-platform ActionSheet with a flexible API.
* [react-native-root-toast](https://github.com/magicismight/react-native-root-toast) ⭐ 2,137 | 🐛 94 | 🌐 JavaScript | 📅 2025-11-07 - Pure JavaScript toast solution.
* [react-native-true-sheet](https://github.com/lodev09/react-native-true-sheet) ⭐ 2,094 | 🐛 13 | 🌐 TypeScript | 📅 2026-11-09 - The true native bottom sheet experience.
* [Burnt](https://github.com/nandorojo/burnt) ⭐ 1,562 | 🐛 20 | 🌐 Java | 📅 2025-12-15 - Native toasts and alerts for iOS and Android.
* [react-native-popup-menu](https://github.com/instea/react-native-popup-menu) ⭐ 1,555 | 🐛 50 | 🌐 JavaScript | 📅 2026-07-23 - Extensible popup menu component.
* [react-native-flash-message](https://github.com/lucasferreira/react-native-flash-message) ⚠️ Archived - Flashbar and top-notification alerts.
* [react-native-notifier](https://github.com/seniv/react-native-notifier) ⭐ 1,435 | 🐛 19 | 🌐 TypeScript | 📅 2025-03-17 - Fast and simple in-app notifications.

### Forms & Keyboard

* [React Hook Form](https://github.com/react-hook-form/react-hook-form) ⭐ 44,920 | 🐛 10 | 🌐 TypeScript | 📅 2026-11-09 - Performant form state management and validation for React and React Native.
* [Formik](https://github.com/jaredpalmer/formik) ⭐ 34,300 | 🐛 841 | 🌐 TypeScript | 📅 2025-11-10 - Build forms without the tears.
* [react-native-keyboard-controller](https://github.com/kirillzyusko/react-native-keyboard-controller) ⭐ 3,763 | 🐛 135 | 🌐 TypeScript | 📅 2026-11-10 - Keyboard manager that works identically on iOS and Android.
* [react-native-picker-select](https://github.com/lawnstarter/react-native-picker-select) ⭐ 1,844 | 🐛 97 | 🌐 JavaScript | 📅 2026-07-20 - Picker emulating the native select interface.
* [react-native-masked-text](https://github.com/bhrott/react-native-masked-text) ⭐ 1,607 | 🐛 101 | 🌐 JavaScript | 📅 2025-04-10 - Masked text and input components.
* [react-native-credit-card-input](https://github.com/sbycrosz/react-native-credit-card-input) ⭐ 1,509 | 🐛 6 | 🌐 TypeScript | 📅 2025-11-10 - Cross-platform credit card input.
* [react-native-autocomplete-input](https://github.com/byteburgers/react-native-autocomplete-input) ⭐ 873 | 🐛 3 | 🌐 TypeScript | 📅 2026-11-07 - Pure JavaScript autocomplete input.
* [react-native-multiple-select](https://github.com/toystars/react-native-multiple-select) ⭐ 591 | 🐛 108 | 🌐 JavaScript | 📅 2026-01-24 - Simple multi-select component.

### Text & Rich Content

* [react-native-live-markdown](https://github.com/Expensify/react-native-live-markdown) ⭐ 1,332 | 🐛 64 | 🌐 TypeScript | 📅 2026-11-11 - Drop-in TextInput replacement with live Markdown formatting, by Expensify.
* [react-native-hyperlink](https://github.com/obipawan/react-native-hyperlink) ⭐ 810 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-19 - Make URLs, emails, and fuzzy links clickable.
* [react-native-markdown-display](https://github.com/iamacup/react-native-markdown-display) ⭐ 791 | 🐛 2 | 🌐 JavaScript | 📅 2026-03-20 - 100% CommonMark-compatible Markdown renderer.
* [react-native-responsive-fontsize](https://github.com/heyman333/react-native-responsive-fontsize) ⭐ 737 | 🐛 13 | 🌐 JavaScript | 📅 2026-01-24 - Responsive font sizes based on device screen size.
* [react-native-html-to-pdf](https://github.com/christopherdro/react-native-html-to-pdf) ⭐ 465 | 🐛 10 | 🌐 Kotlin | 📅 2026-01-29 - Convert HTML strings to PDF documents.

### Image & Camera

* [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) ⭐ 9,660 | 🐛 129 | 🌐 TypeScript | 📅 2026-11-09 - Powerful, high-performance camera library with frame processors.
* [react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker) ⭐ 8,633 | 🐛 353 | 🌐 Java | 📅 2026-10-13 - Native UI for selecting photos and videos.
* [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker) ⭐ 6,350 | 🐛 651 | 🌐 Objective-C | 📅 2026-10-15 - Image picker with camera, cropping, and compression.
* [react-native-camera-kit](https://github.com/teslamotors/react-native-camera-kit) ⭐ 2,710 | 🐛 107 | 🌐 Swift | 📅 2026-08-03 - High-performance camera library with barcode scanning, by Tesla.
* [react-native-image-resizer](https://github.com/bamlab/react-native-image-resizer) ⭐ 1,658 | 🐛 3 | 🌐 Java | 📅 2026-10-09 - Resize local images natively.
* [expo-image](https://docs.expo.dev/versions/latest/sdk/image/) - Fast, modern image component with caching and blurhash support.

### Video & Audio

* [react-native-video](https://github.com/TheWidlarzGroup/react-native-video) ⭐ 7,743 | 🐛 205 | 🌐 TypeScript | 📅 2026-11-11 - The Video component for React Native.
* [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc) ⭐ 4,996 | 🐛 31 | 🌐 Java | 📅 2026-11-11 - WebRTC for React Native.
* [react-native-track-player](https://github.com/doublesymmetry/react-native-track-player) ⭐ 3,708 | 🐛 13 | 🌐 TypeScript | 📅 2026-09-30 - Full-featured audio player: background playback, Android Auto, CarPlay, lock-screen controls.
* [react-native-sound](https://github.com/zmxv/react-native-sound) ⭐ 2,919 | 🐛 255 | 🌐 TypeScript | 📅 2026-02-12 - Play sound clips natively.
* [react-native-audio-api](https://github.com/software-mansion/react-native-audio-api) ⭐ 858 | 🐛 27 | 🌐 C++ | 📅 2026-11-10 - High-performance audio engine implementing the Web Audio API.
* [expo-video](https://docs.expo.dev/versions/latest/sdk/video/) - Modern video playback built for Expo and the New Architecture.

### Maps & Location

* [react-native-maps](https://github.com/react-native-maps/react-native-maps) ⭐ 16,017 | 🐛 99 | 🌐 TypeScript | 📅 2026-11-08 - MapView components for iOS and Android.
* [react-native-background-geolocation](https://github.com/transistorsoft/react-native-background-geolocation) ⭐ 2,949 | 🐛 28 | 🌐 TypeScript | 📅 2026-11-03 - Battery-conscious background location with motion detection.
* [rnmapbox/maps](https://github.com/rnmapbox/maps) ⭐ 2,925 | 🐛 100 | 🌐 Kotlin | 📅 2026-11-09 - Mapbox maps for custom map experiences.
* [react-native-google-places-autocomplete](https://github.com/FaridSafi/react-native-google-places-autocomplete) ⭐ 2,069 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-09 - Customizable Google Places autocomplete.
* [react-native-map-link](https://github.com/tschoffelen/react-native-map-link) ⭐ 823 | 🐛 9 | 🌐 TypeScript | 📅 2026-11-02 - Open the user's preferred maps app.

### Charts

* [react-native-graph](https://github.com/margelo/react-native-graph) ⭐ 2,641 | 🐛 24 | 🌐 TypeScript | 📅 2026-10-13 - Beautiful, high-performance line graphs built with Skia.
* [react-native-gifted-charts](https://github.com/Abhinandan-Kushwaha/react-native-gifted-charts) ⭐ 1,373 | 🐛 103 | 🌐 TypeScript | 📅 2026-11-10 - Bar, line, area, pie, donut, and stacked charts.
* [victory-native-xl](https://github.com/FormidableLabs/victory-native-xl) ⭐ 1,236 | 🐛 91 | 🌐 TypeScript | 📅 2026-10-20 - Charting built on Skia and Reanimated with a focus on performance.

### Animation & Gestures

* [react-native-reanimated](https://github.com/software-mansion/react-native-reanimated) ⭐ 11,066 | 🐛 430 | 🌐 TypeScript | 📅 2026-11-10 - The standard for performant animations, running on the UI thread.
* [react-native-animatable](https://github.com/oblador/react-native-animatable) ⭐ 9,926 | 🐛 169 | 🌐 JavaScript | 📅 2023-10-26 - Declarative transitions and standard animations.
* [react-native-skia](https://github.com/Shopify/react-native-skia) ⭐ 8,779 | 🐛 118 | 🌐 TypeScript | 📅 2026-11-10 - High-performance 2D graphics with the Skia rendering engine.
* [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler) ⭐ 6,805 | 🐛 18 | 🌐 TypeScript | 📅 2026-11-10 - Declarative, native-driven gesture system.
* [Moti](https://github.com/nandorojo/moti) ⭐ 4,551 | 🐛 44 | 🌐 TypeScript | 📅 2025-03-11 - Universal animation library powered by Reanimated, with a Framer Motion-like API.
* [TypeGPU](https://github.com/software-mansion/TypeGPU) ⭐ 3,314 | 🐛 353 | 🌐 TypeScript | 📅 2026-11-10 - Type-safe WebGPU toolkit for advanced GPU work.

### Styling & Design Systems

* [styled-components](https://github.com/styled-components/styled-components) ⭐ 41,046 | 🐛 25 | 🌐 TypeScript | 📅 2026-11-11 - CSS-in-JS styling that also targets React Native.
* [Emotion](https://github.com/emotion-js/emotion) ⭐ 18,022 | 🐛 404 | 🌐 JavaScript | 📅 2026-10-23 - High-performance CSS-in-JS style composition.
* [NativeWind](https://github.com/nativewind/nativewind) ⭐ 8,124 | 🐛 71 | 🌐 JavaScript | 📅 2026-11-02 - Tailwind CSS for React Native.
* [react-native-typography](https://github.com/hectahertz/react-native-typography) ⭐ 3,558 | 🐛 18 | 🌐 JavaScript | 📅 2025-01-12 - Pixel-perfect, native-looking typographic styles.
* [Unistyles](https://github.com/jpudysz/react-native-unistyles) ⭐ 2,974 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-10 - C++-powered StyleSheet superset with themes and breakpoints, built for the New Architecture.
* [react-native-safe-area-context](https://github.com/AppAndFlow/react-native-safe-area-context) ⭐ 2,767 | 🐛 111 | 🌐 TypeScript | 📅 2026-11-04 - Flexible safe area inset handling.
* [react-native-edge-to-edge](https://github.com/zoontek/react-native-edge-to-edge) ⭐ 1,034 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-19 - Effortless edge-to-edge display on Android.
* [Stacks](https://github.com/grapp-dev/stacks) ⭐ 1,030 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-01 - Layout primitives for building consistent UIs.

### Internationalization

* [react-native-localize](https://github.com/zoontek/react-native-localize) ⭐ 2,442 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-13 - Toolbox for app localization: locales, timezones, currencies.

### System & Device

* [react-native-device-info](https://github.com/react-native-device-info/react-native-device-info) ⭐ 6,686 | 🐛 27 | 🌐 TypeScript | 📅 2026-11-09 - Device information for iOS and Android.
* [react-native-config](https://github.com/react-native-config/react-native-config) ⭐ 4,952 | 🐛 310 | 🌐 Ruby | 📅 2026-11-04 - Expose environment config to your JS and native code.
* [react-native-permissions](https://github.com/zoontek/react-native-permissions) ⭐ 4,373 | 🐛 9 | 🌐 Objective-C++ | 📅 2026-10-16 - Unified permissions API.
* [react-native-share](https://github.com/react-native-share/react-native-share) ⭐ 3,897 | 🐛 5 | 🌐 Java | 📅 2026-11-05 - Native share sheet and social sharing.
* [react-native-keychain](https://github.com/oblador/react-native-keychain) ⭐ 3,485 | 🐛 185 | 🌐 Kotlin | 📅 2026-11-06 - Secure keychain and keystore access.
* [react-native-contacts](https://github.com/morenoh149/react-native-contacts) ⭐ 1,711 | 🐛 14 | 🌐 Java | 📅 2026-10-13 - Native contacts access.
* [react-native-background-fetch](https://github.com/transistorsoft/react-native-background-fetch) ⭐ 1,608 | 🐛 2 | 🌐 Java | 📅 2026-11-10 - Periodic background callbacks on iOS and Android.
* [document-picker](https://github.com/react-native-documents/document-picker) ⭐ 1,513 | 🐛 21 | 🌐 TypeScript | 📅 2026-11-06 - Document picker and viewer.
* [react-native-haptic-feedback](https://github.com/mkuczera/react-native-haptic-feedback) ⭐ 982 | 🐛 10 | 🌐 TypeScript | 📅 2026-06-10 - Haptics that feel right, including Core Haptics patterns.
* [react-native-sensors](https://github.com/react-native-sensors/react-native-sensors) ⭐ 935 | 🐛 48 | 🌐 Objective-C | 📅 2026-11-06 - Developer-friendly access to device sensors.
* [react-native-calendar-events](https://github.com/wmcmahan/react-native-calendar-events) ⭐ 930 | 🐛 78 | 🌐 Java | 📅 2026-10-22 - Calendar event access for iOS and Android.
* [expo-quick-actions](https://github.com/EvanBacon/expo-quick-actions) ⭐ 665 | 🐛 14 | 🌐 TypeScript | 📅 2026-09-25 - Home screen quick actions and custom app icons.
* [react-native-ssl-pinning](https://github.com/MaxToyberman/react-native-ssl-pinning) ⭐ 410 | 🐛 77 | 🌐 Java | 📅 2025-07-02 - SSL pinning and cookie handling.
* [react-native-background-downloader](https://github.com/kesha-antonov/react-native-background-downloader) ⭐ 225 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-09 - Download and upload large files, even when the app is backgrounded.

### Notifications

* [react-native-firebase](https://github.com/invertase/react-native-firebase) ⭐ 12,327 | 🐛 76 | 🌐 TypeScript | 📅 2026-11-11 - Includes FCM messaging alongside the full Firebase suite.
* [react-native-notifications](https://github.com/wix/react-native-notifications) ⭐ 3,339 | 🐛 6 | 🌐 Java | 📅 2026-10-05 - Wix's notification handling library.
* [react-native-onesignal](https://github.com/OneSignal/react-native-onesignal) ⭐ 1,590 | 🐛 18 | 🌐 TypeScript | 📅 2026-11-11 - OneSignal push notification SDK.
* [Expo Notifications](https://docs.expo.dev/versions/latest/sdk/notifications/) - Push and local notifications for Expo apps.

### Web & WebViews

* [react-native-web](https://github.com/necolas/react-native-web) ⭐ 22,162 | 🐛 40 | 🌐 JavaScript | 📅 2026-11-10 - Run React Native components and APIs on the web.
* [react-native-webview](https://github.com/react-native-webview/react-native-webview) ⭐ 7,200 | 🐛 106 | 🌐 TypeScript | 📅 2026-11-04 - The community WebView component.
* [Solito](https://github.com/nandorojo/solito) ⭐ 4,093 | 🐛 27 | 🌐 TypeScript | 📅 2026-09-10 - React Native + Next.js, unified navigation for universal apps.
* [react-native-inappbrowser](https://github.com/proyecto26/react-native-inappbrowser) ⭐ 1,416 | 🐛 91 | 🌐 Java | 📅 2026-03-22 - In-app browser using Chrome Custom Tabs and SFSafariViewController.

### Other Platforms

* [react-native-windows](https://github.com/microsoft/react-native-windows) ⭐ 17,376 | 🐛 782 | 🌐 C++ | 📅 2026-11-11 - Build native Windows apps with React.
* [react-native-macos](https://github.com/microsoft/react-native-macos) ⭐ 4,401 | 🐛 146 | 🌐 C++ | 📅 2026-11-11 - Build native macOS apps with React.

## Data

### State Management

* [Zustand](https://github.com/pmndrs/zustand) ⭐ 58,916 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-06 - Bear necessities for state management.
* [Jotai](https://github.com/pmndrs/jotai) ⭐ 21,313 | 🐛 6 | 🌐 TypeScript | 📅 2026-11-09 - Primitive and flexible atomic state.
* [Redux Toolkit](https://github.com/reduxjs/redux-toolkit) ⭐ 11,247 | 🐛 258 | 🌐 TypeScript | 📅 2026-11-08 - The official, batteries-included Redux toolset.
* [Legend State](https://github.com/LegendApp/legend-state) ⭐ 4,226 | 🐛 225 | 🌐 TypeScript | 📅 2026-10-10 - Super fast state with fine-grained reactivity and built-in sync.

### Storage & Databases

* [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) ⭐ 36,264 | 🐛 2,055 | 🌐 TypeScript | 📅 2026-11-11 - TypeScript ORM with first-class Expo/React Native SQLite support.
* [RxDB](https://github.com/pubkey/rxdb) ⭐ 23,422 | 🐛 20 | 🌐 TypeScript | 📅 2026-11-11 - Local-first, reactive database that replicates with your backend.
* [WatermelonDB](https://github.com/Nozbe/WatermelonDB) ⭐ 11,799 | 🐛 317 | 🌐 JavaScript | 📅 2026-09-16 - Reactive and asynchronous database for powerful apps that scale.
* [react-native-mmkv](https://github.com/mrousavy/react-native-mmkv) ⭐ 8,532 | 🐛 26 | 🌐 TypeScript | 📅 2026-11-09 - The fastest key/value storage for React Native, \~30x faster than AsyncStorage.
* [Realm](https://github.com/realm/realm-js) ⭐ 6,003 | 🐛 667 | 🌐 TypeScript | 📅 2026-11-09 - Mobile object database, an alternative to SQLite.
* [AsyncStorage](https://github.com/react-native-async-storage/async-storage) ⭐ 5,073 | 🐛 30 | 🌐 Kotlin | 📅 2026-10-26 - Simple, asynchronous, persistent key-value storage.
* [op-sqlite](https://github.com/OP-Engineering/op-sqlite) ⭐ 1,055 | 🐛 9 | 🌐 C | 📅 2026-11-05 - The fastest SQLite library for React Native.
* [expo-sqlite](https://docs.expo.dev/versions/latest/sdk/sqlite/) - SQLite database access in Expo, with support for Drizzle ORM.

### Networking

* [TanStack Query](https://github.com/TanStack/query) ⭐ 50,560 | 🐛 134 | 🌐 TypeScript | 📅 2026-11-09 - Powerful async state management and data fetching.
* [apisauce](https://github.com/infinitered/apisauce) ⭐ 2,885 | 🐛 48 | 🌐 JavaScript | 📅 2026-06-12 - Axios with standardized errors and request/response transforms.
* [react-native-netinfo](https://github.com/react-native-netinfo/react-native-netinfo) ⭐ 2,180 | 🐛 178 | 🌐 TypeScript | 📅 2026-02-15 - Network state and connectivity info.
* [react-native-quick-crypto](https://github.com/margelo/react-native-quick-crypto) ⭐ 1,074 | 🐛 7 | 🌐 TypeScript | 📅 2026-11-10 - Fast native implementation of Node's crypto module.
* [react-native-network-logger](https://github.com/alexbrazier/react-native-network-logger) ⭐ 688 | 🐛 21 | 🌐 TypeScript | 📅 2026-06-11 - In-app HTTP request monitor.

## Services & Integrations

* [react-native-firebase](https://github.com/invertase/react-native-firebase) ⭐ 12,327 | 🐛 76 | 🌐 TypeScript | 📅 2026-11-11 - Well-tested, feature-rich modular Firebase implementation.
* [google-signin](https://github.com/react-native-google-signin/google-signin) ⭐ 3,554 | 🐛 23 | 🌐 TypeScript | 📅 2026-10-29 - Google Sign-In for React Native.
* [react-native-app-auth](https://github.com/FormidableLabs/react-native-app-auth) ⭐ 2,252 | 🐛 161 | 🌐 Java | 📅 2026-10-19 - PKCE-compliant OAuth2 client based on AppAuth.
* [sentry-react-native](https://github.com/getsentry/sentry-react-native) ⭐ 1,824 | 🐛 131 | 🌐 TypeScript | 📅 2026-11-11 - Official Sentry SDK for crash reporting and performance monitoring.

## Payments & Monetization

* [stripe-react-native](https://github.com/stripe/stripe-react-native) ⭐ 1,431 | 🐛 196 | 🌐 TypeScript | 📅 2026-11-11 - Official Stripe SDK for payments in React Native.
* [react-native-purchases](https://github.com/RevenueCat/react-native-purchases) ⭐ 1,221 | 🐛 95 | 🌐 TypeScript | 📅 2026-11-10 - RevenueCat SDK for in-app purchases and subscriptions.

## Development Tools

### Tooling & IDE

* [react-native-rename](https://github.com/junedomingo/react-native-rename) ⭐ 2,774 | 🐛 28 | 🌐 JavaScript | 📅 2026-08-04 - Rename a React Native app with one command.
* [Re.Pack](https://github.com/callstack/repack) ⭐ 1,947 | 🐛 30 | 🌐 TypeScript | 📅 2026-11-10 - Webpack/Rspack-based toolkit with code splitting and Module Federation for React Native.
* [Radon IDE](https://github.com/software-mansion/radon-ide) ⭐ 1,724 | 🐛 139 | 🌐 TypeScript | 📅 2026-10-23 - VSCode/Cursor extension that turns your editor into a full-featured React Native IDE with an embedded simulator.
* [react-native-bundle-visualizer](https://github.com/callstack/react-native-bundle-visualizer) ⭐ 1,632 | 🐛 1 | 📅 2026-05-27 - See which packages inflate your bundle size.
* [EAS CLI](https://github.com/expo/eas-cli) ⭐ 1,384 | 🐛 481 | 🌐 TypeScript | 📅 2026-11-11 - Build, submit, and update iOS and Android apps from the command line.

### Debugging

* [Reactotron](https://github.com/infinitered/reactotron) ⭐ 15,600 | 🐛 155 | 🌐 TypeScript | 📅 2026-08-13 - Desktop app for inspecting React Native apps: state, API requests, performance.
* [Buoy](https://github.com/Buoy-gg/buoy) ⭐ 696 | 🐛 4 | 📅 2026-11-10 - Devtools that live in your app — and answer to your AI agent.

### Testing

* [Maestro](https://github.com/mobile-dev-inc/Maestro) ⭐ 16,376 | 🐛 460 | 🌐 Kotlin | 📅 2026-11-06 - Painless declarative E2E automation for mobile.
* [Detox](https://github.com/wix/Detox) ⭐ 12,055 | 🐛 191 | 🌐 JavaScript | 📅 2026-11-02 - Gray-box end-to-end testing and automation framework.
* [React Native Testing Library](https://github.com/callstack/react-native-testing-library) ⭐ 3,429 | 🐛 9 | 🌐 TypeScript | 📅 2026-11-09 - Testing utilities that encourage good practices.
* [Loki](https://github.com/oblador/loki) ⭐ 1,917 | 🐛 155 | 🌐 JavaScript | 📅 2026-10-29 - Visual regression testing for Storybook.

### Builds, Deployment & OTA Updates

* [hot-updater](https://github.com/gronxb/hot-updater) ⭐ 1,820 | 🐛 6 | 🌐 TypeScript | 📅 2026-11-10 - Self-hostable OTA update solution, a CodePush alternative.
* [EAS](https://expo.dev/eas) - Expo Application Services: cloud builds, app store submission, and OTA updates.
* [Fastlane](https://fastlane.tools) - Automate building, screenshots, and releasing for iOS and Android.

### Building Libraries

* [create-react-native-library](https://github.com/callstack/react-native-builder-bob) ⭐ 3,232 | 🐛 22 | 🌐 JavaScript | 📅 2026-11-09 - Scaffold and build React Native libraries for distribution.
* [Nitro Modules](https://github.com/mrousavy/nitro) ⭐ 1,976 | 🐛 235 | 🌐 TypeScript | 📅 2026-11-10 - Insanely fast native C++, Swift, or Kotlin modules with statically compiled bindings.

## Starters & Boilerplates

* [Ignite](https://github.com/infinitered/ignite) ⭐ 19,950 | 🐛 40 | 🌐 TypeScript | 📅 2026-06-07 - Infinite Red's battle-tested boilerplate with CLI and generators.
* [react-native-boilerplate](https://github.com/thecodingmachine/react-native-boilerplate) ⭐ 5,563 | 🐛 19 | 🌐 TypeScript | 📅 2026-06-30 - TheCodingMachine's template for solid, scalable applications.
* [Expo Templates](https://docs.expo.dev/more/create-expo/) - Official Expo templates, from blank to tabs to full navigation setups.

## Open Source Apps

Production apps you can learn from.

* [Joplin](https://github.com/laurent22/joplin) ⭐ 57,135 | 🐛 679 | 🌐 TypeScript | 📅 2026-11-11 - Privacy-focused note-taking app with sync, on every platform.
* [Bluesky](https://github.com/bluesky-social/social-app) ⭐ 18,390 | 🐛 2,442 | 🌐 TypeScript | 📅 2026-11-11 - The Bluesky social app for web, iOS, and Android.
* [Expensify](https://github.com/Expensify/App) ⭐ 5,093 | 🐛 2,316 | 🌐 TypeScript | 📅 2026-11-11 - New Expensify: financial collaboration, chat-centered.
* [Artsy](https://github.com/artsy/eigen) ⭐ 3,789 | 🐛 20 | 🌐 TypeScript | 📅 2026-11-11 - The art world in your pocket.
* [Mattermost](https://github.com/mattermost/mattermost-mobile) ⭐ 2,743 | 🐛 341 | 🌐 TypeScript | 📅 2026-11-10 - Mattermost's mobile apps.
* [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat.ReactNative) ⭐ 2,423 | 🐛 545 | 🌐 TypeScript | 📅 2026-11-10 - Rocket.Chat's mobile client.
* [YouTrack Mobile](https://github.com/JetBrains/youtrack-mobile) ⚠️ Archived - JetBrains' YouTrack client for iOS and Android.

## Learning

* [React Native Docs](https://reactnative.dev/docs/getting-started) - The official guides, always the right place to start.
* [Expo Tutorial](https://docs.expo.dev/tutorial/introduction/) - Official hands-on tutorial building a universal app.
* [React Native Express](https://www.reactnative.express) - Guided walkthrough of the React Native ecosystem.
* [Start React Native](https://start-react-native.dev) - William Candillon's in-depth course on gestures and animations.
* [Can it be done in React Native?](https://www.youtube.com/@wcandillon) - William Candillon's YouTube series rebuilding famous UIs.

## Staying Up to Date

* [This Week In React](https://thisweekinreact.com) - Weekly newsletter covering React and React Native.
* [React Native Newsletter](https://reactnativenewsletter.com) - Occasional newsletter of React Native news and articles.
* [React Native Radio](https://reactnativeradio.com) - The long-running React Native podcast, by Infinite Red.
* [Chain React](https://chainreactconf.com) - The US React Native conference, Portland, OR.
* [App.js Conf](https://appjs.co) - Expo and React Native conference, Kraków, Poland.
* [React Universe Conf](https://www.reactuniverseconf.com) - Callstack's conference (formerly React Native EU), Wrocław, Poland.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first: entries should be actively maintained, work with current React Native, and be genuinely useful to most developers.

Many thanks to everyone on the [contributor list](https://github.com/jondot/awesome-react-native/graphs/contributors) :)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-11._
