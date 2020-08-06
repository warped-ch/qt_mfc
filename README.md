# qt_mfc: Qt/MFC migration

## QtWinMigrate examples
* run `...\qt_mfc\qt-solutions\qtwinmigrate>configure.bat -library` to configure QtWinMigrate component to build as a dynamic library
* open `...\qt_mfc\qt-solutions\qtwinmigrate\examples\examples.pro` in Qt Cerator and build (32bit debug & release configuration)

### Example: MFC step1
* open `...\qt_mfc\qt-solutions\qtwinmigrate\examples\mfc\step1\QtMfc.vcxproj`, in VS2019 and build 32bit configuration
* __TODO: hack__ copy `...\qt_mfc\qt-solutions\qtwinmigrate\examples\mfc\step1\Debug\QtMfc.exe` to e.g. `C:\Qt\5.15.0\msvc2019\bin\` and run example from this directory, open Help -> About QtMfc... in order to run the actual Qt dialog

## Resources
* [Qt Documentation](https://doc.qt.io/)
* [MFC Desktop Applications](https://docs.microsoft.com/en-us/cpp/mfc/mfc-desktop-applications?view=vs-2019)
* [Migration from MFC to Qt, Presentation Qt World Summit 2019, Berlin](https://www.kdab.com/wp-content/uploads/stories/Migration-from-MFC-to-Qt.pdf)

### Examples
* [Qt Examples And Tutorials](https://doc.qt.io/qt-5/qtexamplesandtutorials.html)
* [Microsoft MFC samples](https://docs.microsoft.com/en-us/cpp/overview/visual-cpp-samples?view=vs-2019#mfc-samples)

### GitHub
* [qt-qtproject/qt-solutions/qtwinmigrate](https://github.com/qtproject/qt-solutions/tree/master/qtwinmigrate)
* [microsoft/VCSamples](https://github.com/microsoft/VCSamples)
