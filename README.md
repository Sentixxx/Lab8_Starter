# WebURL
https://blog.sentixx.top/Lab8_Starter/

# How are graceful degradation and service workers related?
Service workers implement graceful degradation: when service worker is supported by explorer, we use Service Worker for offline cached resourse for better response speed. when it isn't, we skip the registeration of service worker, use normal method.