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

* [Upgrade Helper](https://github.com/react-native-community/upgrade-helper) ⭐ 4,066 | 🐛 17 | 🌐 TypeScript | 📅 2026-07-23 - Web tool that shows the exact diff between two React Native versions for painless upgrades.
* [Expo Examples](https://github.com/expo/examples) ⭐ 3,721 | 🐛 135 | 🌐 TypeScript | 📅 2026-09-03 - Example projects demonstrating Expo APIs and integrations.
* [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge) ⭐ 1,316 | 🐛 3 | 🌐 Shell | 📅 2026-08-26 - The raw version-to-version diffs powering Upgrade Helper.
* [React Native](https://reactnative.dev) - Official documentation, including environment setup, guides, and API reference.
* [Expo](https://expo.dev) - The recommended framework for building React Native apps: file-based routing, native modules, builds, and updates out of the box.
* [React Native Directory](https://reactnative.directory) - Searchable, filterable directory of React Native libraries with maintenance and New Architecture compatibility signals.

## AI-Assisted Development

Tools for building React Native apps with AI agents, and for putting AI inside your apps.

### Agents & Skills

* [Agent Skills](https://github.com/anthropics/skills) ⭐ 173,772 | 🐛 1,211 | 🌐 Python | 📅 2026-09-03 - Anthropic's public repository of agent skills, usable with Claude Code and other agents.
* [Expo Skills](https://github.com/expo/skills) ⭐ 2,496 | 🐛 61 | 🌐 Shell | 📅 2026-09-03 - Agent skills that give coding agents Expo-specific knowledge and best practices.
* [Expo AI Agents Guide](https://docs.expo.dev/agents/) - Expo's official documentation for AI-native development: agent setup, llms.txt, and best practices.
* [Claude Code + Expo](https://docs.expo.dev/agents/claude/) - Official guide for building, debugging, and deploying Expo apps with Claude Code.

### MCP Servers

* [mobile-mcp](https://github.com/mobile-next/mobile-mcp) ⭐ 6,329 | 🐛 60 | 🌐 TypeScript | 📅 2026-09-03 - MCP server for mobile automation on iOS, Android, emulators, simulators, and real devices.
* [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) ⭐ 2,160 | 🐛 25 | 🌐 JavaScript | 📅 2026-08-13 - MCP server for driving the iOS simulator: interact with UI, take screenshots, inspect the view hierarchy.
* [Expo MCP](https://docs.expo.dev/mcp/) - Expo-hosted MCP server: EAS logs, documentation search, and deployment workflows from any MCP-capable agent.
* [Maestro](https://maestro.dev) - E2E testing framework with a built-in MCP server, letting agents run flows and control devices.

### On-Device AI

* [AI SDK](https://github.com/vercel/ai) ⭐ 26,570 | 🐛 1,503 | 🌐 TypeScript | 📅 2026-09-04 - The AI toolkit for TypeScript; works in Expo and React Native apps for chat, streaming, and tool use.
* [react-native-executorch](https://github.com/software-mansion/react-native-executorch) ⭐ 1,710 | 🐛 49 | 🌐 C++ | 📅 2026-09-03 - Declarative on-device AI inference powered by ExecuTorch, from Software Mansion.
* [react-native-fast-tflite](https://github.com/mrousavy/react-native-fast-tflite) ⭐ 1,233 | 🐛 42 | 🌐 TypeScript | 📅 2026-08-28 - High-performance TensorFlow Lite inference with GPU acceleration.
* [llama.rn](https://github.com/mybigday/llama.rn) ⭐ 1,033 | 🐛 15 | 🌐 C++ | 📅 2026-08-28 - React Native binding of llama.cpp for running LLMs on device.

### AI App Builders

* [a0.dev](https://a0.dev) - Generates complete React Native apps from a prompt and ships them to the app stores.
* [Rork](https://rork.com) - AI app builder that generates Expo/React Native projects compiling to native iOS, Android, and web.

## Components

### UI

* [React Native Elements](https://github.com/react-native-elements/react-native-elements) ⭐ 25,859 | 🐛 156 | 🌐 MDX | 📅 2026-05-21 - Cross-platform UI toolkit with themed, composable components.
* [NativeBase](https://github.com/GeekyAnts/NativeBase) ⭐ 20,380 | 🐛 376 | 🌐 TypeScript | 📅 2026-01-31 - Mobile-first, accessible component library for React Native and web.
* [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) ⭐ 17,915 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-30 - Customizable icon sets with support for styling and image sources.
* [lottie-react-native](https://github.com/lottie-react-native/lottie-react-native) ⭐ 17,210 | 🐛 16 | 🌐 TypeScript | 📅 2026-09-02 - Render After Effects animations natively.
* [react-native-paper](https://github.com/callstack/react-native-paper) ⭐ 14,454 | 🐛 484 | 🌐 TypeScript | 📅 2026-09-03 - Material Design components for Android and iOS.
* [Tamagui](https://github.com/tamagui/tamagui) ⭐ 14,175 | 🐛 88 | 🌐 TypeScript | 📅 2026-09-04 - Universal UI kit and style system with an optimizing compiler, 100% parity between React Native and web.
* [react-native-ui-kitten](https://github.com/akveo/react-native-ui-kitten) ⭐ 10,670 | 🐛 134 | 🌐 TypeScript | 📅 2026-08-07 - UI library based on the Eva Design System with theming support.
* [react-native-calendars](https://github.com/wix/react-native-calendars) ⭐ 10,310 | 🐛 149 | 🌐 TypeScript | 📅 2026-04-23 - Feature-rich calendar components.
* [react-native-svg](https://github.com/software-mansion/react-native-svg) ⭐ 8,002 | 🐛 256 | 🌐 TypeScript | 📅 2026-09-01 - SVG rendering for React Native and web.
* [react-native-modal](https://github.com/react-native-modal/react-native-modal) ⭐ 5,654 | 🐛 99 | 🌐 TypeScript | 📅 2026-01-29 - Enhanced, animated, customizable modal.
* [gluestack-ui](https://github.com/gluestack/gluestack-ui) ⭐ 5,283 | 🐛 16 | 🌐 TypeScript | 📅 2026-09-02 - Copy-paste components and patterns built on Tailwind-style utility classes.
* [Shoutem UI](https://github.com/shoutem/ui) ⭐ 4,979 | 🐛 103 | 🌐 JavaScript | 📅 2026-08-21 - Customizable set of styled components for React Native.
* [react-native-blur](https://github.com/margelo/react-native-blur) ⭐ 3,882 | 🐛 250 | 🌐 TypeScript | 📅 2026-05-09 - Native blur view component.
* [react-native-reanimated-carousel](https://github.com/dohooo/react-native-reanimated-carousel) ⭐ 3,431 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-08 - Swiper/carousel built entirely on Reanimated, the successor to snap-carousel.
* [react-native-pager-view](https://github.com/callstack/react-native-pager-view) ⭐ 3,357 | 🐛 143 | 🌐 TypeScript | 📅 2026-09-01 - Native ViewPager and UIPageViewController wrapper.
* [react-native-date-picker](https://github.com/henninghall/react-native-date-picker) ⭐ 2,506 | 🐛 80 | 🌐 Java | 📅 2025-06-05 - Native date and time picker for Android and iOS.
* [react-native-copilot](https://github.com/mohebifar/react-native-copilot) ⭐ 2,437 | 🐛 124 | 🌐 TypeScript | 📅 2024-12-17 - Step-by-step walkthrough tooltips for onboarding.
* [react-native-circular-progress](https://github.com/bartgryszko/react-native-circular-progress) ⭐ 2,249 | 🐛 74 | 🌐 JavaScript | 📅 2025-08-13 - Animated circular progress indicators.
* [react-native-blurhash](https://github.com/mrousavy/react-native-blurhash) ⭐ 2,239 | 🐛 32 | 🌐 Kotlin | 📅 2026-03-19 - Colorful blurry placeholders while content loads.
* [react-native-svg-transformer](https://github.com/kristerkari/react-native-svg-transformer) ⭐ 1,736 | 🐛 89 | 🌐 JavaScript | 📅 2026-09-03 - Import SVG files as components, like on the web.
* [react-native-super-grid](https://github.com/saleel/react-native-super-grid) ⭐ 1,482 | 🐛 12 | 🌐 JavaScript | 📅 2025-11-26 - Responsive grid view.
* [react-native-confirmation-code-field](https://github.com/retyui/react-native-confirmation-code-field) ⭐ 1,229 | 🐛 5 | 🌐 TypeScript | 📅 2026-03-31 - OTP/confirmation code input for iOS, Android, and web.
* [react-native-qrcode-svg](https://github.com/Expensify/react-native-qrcode-svg) ⭐ 1,173 | 🐛 57 | 🌐 JavaScript | 📅 2026-09-02 - QR code generator based on react-native-svg.
* [react-native-country-picker-modal](https://github.com/xcarpentier/react-native-country-picker-modal) ⭐ 1,112 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-03 - Country picker with flags, search, and localization.
* [react-native-hole-view](https://github.com/ibitcy/react-native-hole-view) ⭐ 446 | 🐛 6 | 🌐 TypeScript | 📅 2026-01-19 - Cut touch-through holes anywhere, perfect for onboarding highlights.
* [react-native-progress-steps](https://github.com/colbymillerdev/react-native-progress-steps) ⭐ 395 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-20 - Customizable progress stepper.

### Lists

* [FlashList](https://github.com/Shopify/flash-list) ⭐ 7,195 | 🐛 193 | 🌐 TypeScript | 📅 2026-09-04 - Shopify's fast and performant list, a drop-in replacement for FlatList.
* [recyclerlistview](https://github.com/Flipkart/recyclerlistview) ⭐ 5,433 | 🐛 264 | 🌐 TypeScript | 📅 2025-03-16 - The recycling listview that pioneered high-performance lists in React Native.
* [Legend List](https://github.com/LegendApp/legend-list) ⭐ 3,340 | 🐛 83 | 🌐 TypeScript | 📅 2026-09-01 - High-performance list in pure JS, built for the New Architecture.

### Navigation

* [React Navigation](https://github.com/react-navigation/react-navigation) ⭐ 24,504 | 🐛 844 | 🌐 TypeScript | 📅 2026-08-26 - The standard routing and navigation library for React Native.
* [react-native-navigation](https://github.com/wix/react-native-navigation) ⭐ 13,176 | 🐛 61 | 🌐 MDX | 📅 2026-09-03 - Wix's fully native navigation solution.
* [react-native-screens](https://github.com/software-mansion/react-native-screens) ⭐ 3,726 | 🐛 282 | 🌐 TypeScript | 📅 2026-09-04 - Native navigation primitives that back React Navigation's native stack.
* [react-native-bottom-tabs](https://github.com/callstack/react-native-bottom-tabs) ⭐ 1,449 | 🐛 47 | 🌐 TypeScript | 📅 2026-09-04 - Truly native bottom tab bars (SwiftUI and Material) for React Native.
* [Expo Router](https://docs.expo.dev/router/introduction/) - File-based routing for universal React Native apps, built on React Navigation.

### Sheets, Menus & Toasts

* [react-native-bottom-sheet](https://github.com/gorhom/react-native-bottom-sheet) ⭐ 9,084 | 🐛 83 | 🌐 TypeScript | 📅 2026-05-09 - Performant, interactive bottom sheet with configurable gestures.
* [Zeego](https://github.com/nandorojo/zeego) ⭐ 2,253 | 🐛 49 | 🌐 TypeScript | 📅 2026-01-28 - Menus for React Native done right — truly native dropdown and context menus.
* [react-native-actions-sheet](https://github.com/ammarahm-ed/react-native-actions-sheet) ⭐ 2,177 | 🐛 110 | 🌐 TypeScript | 📅 2026-04-23 - Cross-platform ActionSheet with a flexible API.
* [react-native-root-toast](https://github.com/magicismight/react-native-root-toast) ⭐ 2,136 | 🐛 95 | 🌐 JavaScript | 📅 2025-11-07 - Pure JavaScript toast solution.
* [react-native-true-sheet](https://github.com/lodev09/react-native-true-sheet) ⭐ 2,050 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-03 - The true native bottom sheet experience.
* [Burnt](https://github.com/nandorojo/burnt) ⭐ 1,562 | 🐛 21 | 🌐 Java | 📅 2025-12-15 - Native toasts and alerts for iOS and Android.
* [react-native-popup-menu](https://github.com/instea/react-native-popup-menu) ⭐ 1,557 | 🐛 48 | 🌐 JavaScript | 📅 2026-07-23 - Extensible popup menu component.
* [react-native-flash-message](https://github.com/lucasferreira/react-native-flash-message) ⭐ 1,530 | 🐛 24 | 🌐 JavaScript | 📅 2024-12-16 - Flashbar and top-notification alerts.
* [react-native-notifier](https://github.com/seniv/react-native-notifier) ⭐ 1,438 | 🐛 19 | 🌐 TypeScript | 📅 2025-03-17 - Fast and simple in-app notifications.

### Forms & Keyboard

* [React Hook Form](https://github.com/react-hook-form/react-hook-form) ⭐ 44,848 | 🐛 6 | 🌐 TypeScript | 📅 2026-09-03 - Performant form state management and validation for React and React Native.
* [Formik](https://github.com/jaredpalmer/formik) ⭐ 34,328 | 🐛 840 | 🌐 TypeScript | 📅 2025-11-10 - Build forms without the tears.
* [react-native-keyboard-controller](https://github.com/kirillzyusko/react-native-keyboard-controller) ⭐ 3,711 | 🐛 127 | 🌐 TypeScript | 📅 2026-09-03 - Keyboard manager that works identically on iOS and Android.
* [react-native-picker-select](https://github.com/lawnstarter/react-native-picker-select) ⭐ 1,846 | 🐛 95 | 🌐 JavaScript | 📅 2026-07-20 - Picker emulating the native select interface.
* [react-native-masked-text](https://github.com/bhrott/react-native-masked-text) ⭐ 1,607 | 🐛 101 | 🌐 JavaScript | 📅 2025-04-10 - Masked text and input components.
* [react-native-credit-card-input](https://github.com/sbycrosz/react-native-credit-card-input) ⭐ 1,508 | 🐛 6 | 🌐 TypeScript | 📅 2025-11-10 - Cross-platform credit card input.
* [react-native-autocomplete-input](https://github.com/byteburgers/react-native-autocomplete-input) ⭐ 871 | 🐛 10 | 🌐 TypeScript | 📅 2026-09-03 - Pure JavaScript autocomplete input.
* [react-native-multiple-select](https://github.com/toystars/react-native-multiple-select) ⭐ 589 | 🐛 108 | 🌐 JavaScript | 📅 2026-01-24 - Simple multi-select component.

### Text & Rich Content

* [react-native-live-markdown](https://github.com/Expensify/react-native-live-markdown) ⭐ 1,337 | 🐛 61 | 🌐 TypeScript | 📅 2026-09-02 - Drop-in TextInput replacement with live Markdown formatting, by Expensify.
* [react-native-hyperlink](https://github.com/obipawan/react-native-hyperlink) ⭐ 812 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-19 - Make URLs, emails, and fuzzy links clickable.
* [react-native-markdown-display](https://github.com/iamacup/react-native-markdown-display) ⭐ 792 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-20 - 100% CommonMark-compatible Markdown renderer.
* [react-native-responsive-fontsize](https://github.com/heyman333/react-native-responsive-fontsize) ⭐ 740 | 🐛 13 | 🌐 JavaScript | 📅 2026-01-24 - Responsive font sizes based on device screen size.
* [react-native-html-to-pdf](https://github.com/christopherdro/react-native-html-to-pdf) ⭐ 462 | 🐛 8 | 🌐 Kotlin | 📅 2026-01-29 - Convert HTML strings to PDF documents.

### Image & Camera

* [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) ⭐ 9,609 | 🐛 75 | 🌐 TypeScript | 📅 2026-08-31 - Powerful, high-performance camera library with frame processors.
* [react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker) ⭐ 8,634 | 🐛 348 | 🌐 Java | 📅 2026-03-17 - Native UI for selecting photos and videos.
* [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker) ⭐ 6,350 | 🐛 655 | 🌐 Objective-C | 📅 2026-01-21 - Image picker with camera, cropping, and compression.
* [react-native-camera-kit](https://github.com/teslamotors/react-native-camera-kit) ⭐ 2,705 | 🐛 102 | 🌐 Swift | 📅 2026-08-03 - High-performance camera library with barcode scanning, by Tesla.
* [react-native-image-resizer](https://github.com/bamlab/react-native-image-resizer) ⭐ 1,661 | 🐛 4 | 🌐 Java | 📅 2026-08-22 - Resize local images natively.
* [expo-image](https://docs.expo.dev/versions/latest/sdk/image/) - Fast, modern image component with caching and blurhash support.

### Video & Audio

* [react-native-video](https://github.com/TheWidlarzGroup/react-native-video) ⭐ 7,716 | 🐛 178 | 🌐 Kotlin | 📅 2026-09-01 - The Video component for React Native.
* [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc) ⭐ 4,992 | 🐛 33 | 🌐 Java | 📅 2026-09-03 - WebRTC for React Native.
* [react-native-track-player](https://github.com/doublesymmetry/react-native-track-player) ⭐ 3,707 | 🐛 18 | 🌐 TypeScript | 📅 2026-07-31 - Full-featured audio player: background playback, Android Auto, CarPlay, lock-screen controls.
* [react-native-sound](https://github.com/zmxv/react-native-sound) ⭐ 2,918 | 🐛 253 | 🌐 TypeScript | 📅 2026-02-12 - Play sound clips natively.
* [react-native-audio-api](https://github.com/software-mansion/react-native-audio-api) ⭐ 836 | 🐛 40 | 🌐 C++ | 📅 2026-09-03 - High-performance audio engine implementing the Web Audio API.
* [expo-video](https://docs.expo.dev/versions/latest/sdk/video/) - Modern video playback built for Expo and the New Architecture.

### Maps & Location

* [react-native-maps](https://github.com/react-native-maps/react-native-maps) ⭐ 15,994 | 🐛 98 | 🌐 TypeScript | 📅 2026-09-03 - MapView components for iOS and Android.
* [react-native-background-geolocation](https://github.com/transistorsoft/react-native-background-geolocation) ⭐ 2,921 | 🐛 31 | 🌐 TypeScript | 📅 2026-08-30 - Battery-conscious background location with motion detection.
* [rnmapbox/maps](https://github.com/rnmapbox/maps) ⭐ 2,909 | 🐛 159 | 🌐 Kotlin | 📅 2026-07-22 - Mapbox maps for custom map experiences.
* [react-native-google-places-autocomplete](https://github.com/FaridSafi/react-native-google-places-autocomplete) ⭐ 2,071 | 🐛 118 | 🌐 JavaScript | 📅 2026-08-24 - Customizable Google Places autocomplete.
* [react-native-map-link](https://github.com/tschoffelen/react-native-map-link) ⭐ 821 | 🐛 6 | 🌐 TypeScript | 📅 2026-09-03 - Open the user's preferred maps app.

### Charts

* [react-native-graph](https://github.com/margelo/react-native-graph) ⭐ 2,613 | 🐛 47 | 🌐 TypeScript | 📅 2026-09-02 - Beautiful, high-performance line graphs built with Skia.
* [react-native-gifted-charts](https://github.com/Abhinandan-Kushwaha/react-native-gifted-charts) ⭐ 1,363 | 🐛 99 | 🌐 TypeScript | 📅 2026-08-10 - Bar, line, area, pie, donut, and stacked charts.
* [victory-native-xl](https://github.com/FormidableLabs/victory-native-xl) ⭐ 1,221 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-31 - Charting built on Skia and Reanimated with a focus on performance.

### Animation & Gestures

* [react-native-reanimated](https://github.com/software-mansion/react-native-reanimated) ⭐ 10,975 | 🐛 321 | 🌐 TypeScript | 📅 2026-09-03 - The standard for performant animations, running on the UI thread.
* [react-native-animatable](https://github.com/oblador/react-native-animatable) ⭐ 9,934 | 🐛 172 | 🌐 JavaScript | 📅 2023-10-26 - Declarative transitions and standard animations.
* [react-native-skia](https://github.com/Shopify/react-native-skia) ⭐ 8,541 | 🐛 83 | 🌐 TypeScript | 📅 2026-09-03 - High-performance 2D graphics with the Skia rendering engine.
* [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler) ⭐ 6,783 | 🐛 19 | 🌐 TypeScript | 📅 2026-09-02 - Declarative, native-driven gesture system.
* [Moti](https://github.com/nandorojo/moti) ⭐ 4,549 | 🐛 44 | 🌐 TypeScript | 📅 2025-03-11 - Universal animation library powered by Reanimated, with a Framer Motion-like API.
* [TypeGPU](https://github.com/software-mansion/TypeGPU) ⭐ 3,162 | 🐛 263 | 🌐 TypeScript | 📅 2026-09-03 - Type-safe WebGPU toolkit for advanced GPU work.

### Styling & Design Systems

* [styled-components](https://github.com/styled-components/styled-components) ⭐ 41,124 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-28 - CSS-in-JS styling that also targets React Native.
* [Emotion](https://github.com/emotion-js/emotion) ⭐ 18,021 | 🐛 393 | 🌐 JavaScript | 📅 2026-08-28 - High-performance CSS-in-JS style composition.
* [NativeWind](https://github.com/nativewind/nativewind) ⭐ 8,079 | 🐛 68 | 🌐 TypeScript | 📅 2026-07-17 - Tailwind CSS for React Native.
* [react-native-typography](https://github.com/hectahertz/react-native-typography) ⭐ 3,558 | 🐛 18 | 🌐 JavaScript | 📅 2025-01-12 - Pixel-perfect, native-looking typographic styles.
* [Unistyles](https://github.com/jpudysz/react-native-unistyles) ⭐ 2,939 | 🐛 45 | 🌐 TypeScript | 📅 2026-08-13 - C++-powered StyleSheet superset with themes and breakpoints, built for the New Architecture.
* [react-native-safe-area-context](https://github.com/AppAndFlow/react-native-safe-area-context) ⭐ 2,756 | 🐛 103 | 🌐 TypeScript | 📅 2026-09-03 - Flexible safe area inset handling.
* [react-native-edge-to-edge](https://github.com/zoontek/react-native-edge-to-edge) ⭐ 1,036 | 🐛 4 | 🌐 TypeScript | 📅 2026-07-23 - Effortless edge-to-edge display on Android.
* [Stacks](https://github.com/grapp-dev/stacks) ⭐ 1,028 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-01 - Layout primitives for building consistent UIs.

### Internationalization

* [react-native-localize](https://github.com/zoontek/react-native-localize) ⭐ 2,442 | 🐛 7 | 🌐 TypeScript | 📅 2026-09-03 - Toolbox for app localization: locales, timezones, currencies.

### System & Device

* [react-native-device-info](https://github.com/react-native-device-info/react-native-device-info) ⭐ 6,680 | 🐛 19 | 🌐 TypeScript | 📅 2026-09-03 - Device information for iOS and Android.
* [react-native-config](https://github.com/react-native-config/react-native-config) ⭐ 4,956 | 🐛 285 | 🌐 Ruby | 📅 2026-08-30 - Expose environment config to your JS and native code.
* [react-native-permissions](https://github.com/zoontek/react-native-permissions) ⭐ 4,379 | 🐛 8 | 🌐 Objective-C++ | 📅 2026-07-23 - Unified permissions API.
* [react-native-share](https://github.com/react-native-share/react-native-share) ⭐ 3,894 | 🐛 18 | 🌐 Java | 📅 2026-08-31 - Native share sheet and social sharing.
* [react-native-keychain](https://github.com/oblador/react-native-keychain) ⭐ 3,475 | 🐛 190 | 🌐 Kotlin | 📅 2026-04-29 - Secure keychain and keystore access.
* [react-native-contacts](https://github.com/morenoh149/react-native-contacts) ⭐ 1,704 | 🐛 5 | 🌐 Java | 📅 2026-09-03 - Native contacts access.
* [react-native-background-fetch](https://github.com/transistorsoft/react-native-background-fetch) ⭐ 1,609 | 🐛 2 | 🌐 Java | 📅 2026-04-22 - Periodic background callbacks on iOS and Android.
* [document-picker](https://github.com/react-native-documents/document-picker) ⭐ 1,516 | 🐛 20 | 🌐 TypeScript | 📅 2026-09-03 - Document picker and viewer.
* [react-native-haptic-feedback](https://github.com/mkuczera/react-native-haptic-feedback) ⭐ 978 | 🐛 9 | 🌐 TypeScript | 📅 2026-06-10 - Haptics that feel right, including Core Haptics patterns.
* [react-native-sensors](https://github.com/react-native-sensors/react-native-sensors) ⭐ 934 | 🐛 49 | 🌐 Objective-C | 📅 2026-09-03 - Developer-friendly access to device sensors.
* [react-native-calendar-events](https://github.com/wmcmahan/react-native-calendar-events) ⭐ 930 | 🐛 78 | 🌐 Java | 📅 2026-01-05 - Calendar event access for iOS and Android.
* [expo-quick-actions](https://github.com/EvanBacon/expo-quick-actions) ⭐ 656 | 🐛 22 | 🌐 TypeScript | 📅 2026-05-27 - Home screen quick actions and custom app icons.
* [react-native-ssl-pinning](https://github.com/MaxToyberman/react-native-ssl-pinning) ⭐ 408 | 🐛 76 | 🌐 Java | 📅 2025-07-02 - SSL pinning and cookie handling.
* [react-native-background-downloader](https://github.com/kesha-antonov/react-native-background-downloader) ⭐ 215 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-06 - Download and upload large files, even when the app is backgrounded.

### Notifications

* [react-native-firebase](https://github.com/invertase/react-native-firebase) ⭐ 12,302 | 🐛 48 | 🌐 TypeScript | 📅 2026-09-04 - Includes FCM messaging alongside the full Firebase suite.
* [react-native-notifications](https://github.com/wix/react-native-notifications) ⭐ 3,341 | 🐛 9 | 🌐 Java | 📅 2026-04-02 - Wix's notification handling library.
* [react-native-onesignal](https://github.com/OneSignal/react-native-onesignal) ⭐ 1,592 | 🐛 21 | 🌐 TypeScript | 📅 2026-09-03 - OneSignal push notification SDK.
* [Expo Notifications](https://docs.expo.dev/versions/latest/sdk/notifications/) - Push and local notifications for Expo apps.

### Web & WebViews

* [react-native-web](https://github.com/necolas/react-native-web) ⭐ 22,141 | 🐛 166 | 🌐 JavaScript | 📅 2025-10-16 - Run React Native components and APIs on the web.
* [react-native-webview](https://github.com/react-native-webview/react-native-webview) ⭐ 7,191 | 🐛 74 | 🌐 TypeScript | 📅 2026-07-12 - The community WebView component.
* [Solito](https://github.com/nandorojo/solito) ⭐ 4,091 | 🐛 27 | 🌐 TypeScript | 📅 2026-08-31 - React Native + Next.js, unified navigation for universal apps.
* [react-native-inappbrowser](https://github.com/proyecto26/react-native-inappbrowser) ⭐ 1,416 | 🐛 91 | 🌐 Java | 📅 2026-03-22 - In-app browser using Chrome Custom Tabs and SFSafariViewController.

### Other Platforms

* [react-native-windows](https://github.com/microsoft/react-native-windows) ⭐ 17,339 | 🐛 803 | 🌐 C++ | 📅 2026-09-03 - Build native Windows apps with React.
* [react-native-macos](https://github.com/microsoft/react-native-macos) ⭐ 4,384 | 🐛 107 | 🌐 C++ | 📅 2026-09-03 - Build native macOS apps with React.

## Data

### State Management

* [Zustand](https://github.com/pmndrs/zustand) ⭐ 58,640 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-31 - Bear necessities for state management.
* [Jotai](https://github.com/pmndrs/jotai) ⭐ 21,251 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-24 - Primitive and flexible atomic state.
* [Redux Toolkit](https://github.com/reduxjs/redux-toolkit) ⭐ 11,223 | 🐛 303 | 🌐 TypeScript | 📅 2026-09-01 - The official, batteries-included Redux toolset.
* [Legend State](https://github.com/LegendApp/legend-state) ⭐ 4,193 | 🐛 216 | 🌐 TypeScript | 📅 2026-08-11 - Super fast state with fine-grained reactivity and built-in sync.

### Storage & Databases

* [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) ⭐ 35,674 | 🐛 1,999 | 🌐 TypeScript | 📅 2026-09-03 - TypeScript ORM with first-class Expo/React Native SQLite support.
* [RxDB](https://github.com/pubkey/rxdb) ⭐ 23,372 | 🐛 19 | 🌐 TypeScript | 📅 2026-09-03 - Local-first, reactive database that replicates with your backend.
* [WatermelonDB](https://github.com/Nozbe/WatermelonDB) ⭐ 11,780 | 🐛 302 | 🌐 JavaScript | 📅 2025-08-11 - Reactive and asynchronous database for powerful apps that scale.
* [react-native-mmkv](https://github.com/mrousavy/react-native-mmkv) ⭐ 8,493 | 🐛 18 | 🌐 TypeScript | 📅 2026-09-03 - The fastest key/value storage for React Native, \~30x faster than AsyncStorage.
* [Realm](https://github.com/realm/realm-js) ⭐ 6,004 | 🐛 658 | 🌐 TypeScript | 📅 2026-08-29 - Mobile object database, an alternative to SQLite.
* [AsyncStorage](https://github.com/react-native-async-storage/async-storage) ⭐ 5,071 | 🐛 27 | 🌐 Kotlin | 📅 2026-09-04 - Simple, asynchronous, persistent key-value storage.
* [op-sqlite](https://github.com/OP-Engineering/op-sqlite) ⭐ 1,032 | 🐛 6 | 🌐 C | 📅 2026-08-21 - The fastest SQLite library for React Native.
* [expo-sqlite](https://docs.expo.dev/versions/latest/sdk/sqlite/) - SQLite database access in Expo, with support for Drizzle ORM.

### Networking

* [TanStack Query](https://github.com/TanStack/query) ⭐ 50,261 | 🐛 155 | 🌐 TypeScript | 📅 2026-09-04 - Powerful async state management and data fetching.
* [apisauce](https://github.com/infinitered/apisauce) ⭐ 2,886 | 🐛 47 | 🌐 JavaScript | 📅 2026-06-12 - Axios with standardized errors and request/response transforms.
* [react-native-netinfo](https://github.com/react-native-netinfo/react-native-netinfo) ⭐ 2,180 | 🐛 173 | 🌐 TypeScript | 📅 2026-02-15 - Network state and connectivity info.
* [react-native-quick-crypto](https://github.com/margelo/react-native-quick-crypto) ⭐ 1,068 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-15 - Fast native implementation of Node's crypto module.
* [react-native-network-logger](https://github.com/alexbrazier/react-native-network-logger) ⭐ 687 | 🐛 20 | 🌐 TypeScript | 📅 2026-06-11 - In-app HTTP request monitor.

## Services & Integrations

* [react-native-firebase](https://github.com/invertase/react-native-firebase) ⭐ 12,302 | 🐛 48 | 🌐 TypeScript | 📅 2026-09-04 - Well-tested, feature-rich modular Firebase implementation.
* [google-signin](https://github.com/react-native-google-signin/google-signin) ⭐ 3,553 | 🐛 23 | 🌐 TypeScript | 📅 2026-09-03 - Google Sign-In for React Native.
* [react-native-app-auth](https://github.com/FormidableLabs/react-native-app-auth) ⭐ 2,256 | 🐛 156 | 🌐 Java | 📅 2026-07-06 - PKCE-compliant OAuth2 client based on AppAuth.
* [sentry-react-native](https://github.com/getsentry/sentry-react-native) ⭐ 1,820 | 🐛 135 | 🌐 TypeScript | 📅 2026-09-04 - Official Sentry SDK for crash reporting and performance monitoring.

## Payments & Monetization

* [stripe-react-native](https://github.com/stripe/stripe-react-native) ⭐ 1,429 | 🐛 200 | 🌐 TypeScript | 📅 2026-09-04 - Official Stripe SDK for payments in React Native.
* [react-native-purchases](https://github.com/RevenueCat/react-native-purchases) ⭐ 1,204 | 🐛 79 | 🌐 TypeScript | 📅 2026-09-03 - RevenueCat SDK for in-app purchases and subscriptions.

## Development Tools

### Tooling & IDE

* [react-native-rename](https://github.com/junedomingo/react-native-rename) ⭐ 2,777 | 🐛 28 | 🌐 JavaScript | 📅 2026-08-04 - Rename a React Native app with one command.
* [Re.Pack](https://github.com/callstack/repack) ⭐ 1,933 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-31 - Webpack/Rspack-based toolkit with code splitting and Module Federation for React Native.
* [Radon IDE](https://github.com/software-mansion/radon-ide) ⭐ 1,717 | 🐛 144 | 🌐 TypeScript | 📅 2026-08-26 - VSCode/Cursor extension that turns your editor into a full-featured React Native IDE with an embedded simulator.
* [react-native-bundle-visualizer](https://github.com/callstack/react-native-bundle-visualizer) ⭐ 1,630 | 🐛 1 | 📅 2026-05-27 - See which packages inflate your bundle size.
* [EAS CLI](https://github.com/expo/eas-cli) ⭐ 1,350 | 🐛 455 | 🌐 TypeScript | 📅 2026-09-04 - Build, submit, and update iOS and Android apps from the command line.

### Debugging

* [Reactotron](https://github.com/infinitered/reactotron) ⭐ 15,590 | 🐛 155 | 🌐 TypeScript | 📅 2026-08-13 - Desktop app for inspecting React Native apps: state, API requests, performance.
* [Buoy](https://github.com/Buoy-gg/buoy) ⭐ 691 | 🐛 4 | 📅 2026-09-03 - Devtools that live in your app — and answer to your AI agent.

### Testing

* [Maestro](https://github.com/mobile-dev-inc/Maestro) ⭐ 15,503 | 🐛 500 | 🌐 Kotlin | 📅 2026-09-03 - Painless declarative E2E automation for mobile.
* [Detox](https://github.com/wix/Detox) ⭐ 12,022 | 🐛 206 | 🌐 JavaScript | 📅 2026-08-24 - Gray-box end-to-end testing and automation framework.
* [React Native Testing Library](https://github.com/callstack/react-native-testing-library) ⭐ 3,417 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-13 - Testing utilities that encourage good practices.
* [Loki](https://github.com/oblador/loki) ⭐ 1,909 | 🐛 140 | 🌐 JavaScript | 📅 2024-10-12 - Visual regression testing for Storybook.

### Builds, Deployment & OTA Updates

* [hot-updater](https://github.com/gronxb/hot-updater) ⭐ 1,695 | 🐛 18 | 🌐 TypeScript | 📅 2026-09-04 - Self-hostable OTA update solution, a CodePush alternative.
* [EAS](https://expo.dev/eas) - Expo Application Services: cloud builds, app store submission, and OTA updates.
* [Fastlane](https://fastlane.tools) - Automate building, screenshots, and releasing for iOS and Android.

### Building Libraries

* [create-react-native-library](https://github.com/callstack/react-native-builder-bob) ⭐ 3,226 | 🐛 24 | 🌐 JavaScript | 📅 2026-08-04 - Scaffold and build React Native libraries for distribution.
* [Nitro Modules](https://github.com/mrousavy/nitro) ⭐ 1,925 | 🐛 183 | 🌐 C++ | 📅 2026-09-03 - Insanely fast native C++, Swift, or Kotlin modules with statically compiled bindings.

## Starters & Boilerplates

* [Ignite](https://github.com/infinitered/ignite) ⭐ 19,939 | 🐛 34 | 🌐 TypeScript | 📅 2026-06-07 - Infinite Red's battle-tested boilerplate with CLI and generators.
* [react-native-boilerplate](https://github.com/thecodingmachine/react-native-boilerplate) ⭐ 5,563 | 🐛 19 | 🌐 TypeScript | 📅 2026-06-30 - TheCodingMachine's template for solid, scalable applications.
* [Expo Templates](https://docs.expo.dev/more/create-expo/) - Official Expo templates, from blank to tabs to full navigation setups.

## Open Source Apps

Production apps you can learn from.

* [Joplin](https://github.com/laurent22/joplin) ⭐ 56,233 | 🐛 645 | 🌐 TypeScript | 📅 2026-09-03 - Privacy-focused note-taking app with sync, on every platform.
* [Bluesky](https://github.com/bluesky-social/social-app) ⭐ 18,263 | 🐛 2,380 | 🌐 TypeScript | 📅 2026-09-04 - The Bluesky social app for web, iOS, and Android.
* [Expensify](https://github.com/Expensify/App) ⭐ 5,016 | 🐛 2,226 | 🌐 TypeScript | 📅 2026-09-04 - New Expensify: financial collaboration, chat-centered.
* [Artsy](https://github.com/artsy/eigen) ⭐ 3,773 | 🐛 24 | 🌐 TypeScript | 📅 2026-09-04 - The art world in your pocket.
* [Mattermost](https://github.com/mattermost/mattermost-mobile) ⭐ 2,715 | 🐛 324 | 🌐 TypeScript | 📅 2026-09-04 - Mattermost's mobile apps.
* [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat.ReactNative) ⭐ 2,413 | 🐛 481 | 🌐 TypeScript | 📅 2026-09-04 - Rocket.Chat's mobile client.
* [YouTrack Mobile](https://github.com/JetBrains/youtrack-mobile) ⭐ 285 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-05 - JetBrains' YouTrack client for iOS and Android.

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

Many thanks to everyone on the [contributor list](https://github.com/jondot/awesome-react-native/graphs/contributors) ⭐ 35,694 | 🐛 15 | 📅 2026-08-26 :)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
