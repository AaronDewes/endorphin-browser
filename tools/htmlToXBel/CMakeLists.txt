project(htmlToXBel)
find_package(Qt5Widgets REQUIRED)
find_package(Qt5Core REQUIRED)
find_package(Qt5Gui REQUIRED)
find_package(Qt5WebEngine REQUIRED)
find_package(Qt5Network REQUIRED)
find_package(Qt5WebEngineWidgets REQUIRED)
add_executable(htmlToXBel main.cpp mainapp.cpp source.qrc)
qt5_use_modules(htmlToXBel Core)
qt5_use_modules(htmlToXBel Widgets)
qt5_use_modules(htmlToXBel Sql)
qt5_use_modules(htmlToXBel WebEngine)
qt5_use_modules(htmlToXBel Network)
qt5_use_modules(htmlToXBel WebEngineWidgets)
