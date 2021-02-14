# camera2Test
It is an example to show how to use camera2API to open camera and take a video correctly

## CameraDevice & CameraDevice.StateCallback
 ### CameraDevice
 * createCaptureRequest(template) - 
 * createCaptureSession(surfaces, new CameraCaptureSession.StateCallback()) - 
 ### CameraCaptureSession
 * setRepeatingRequest(
 ### CameraCaptureSession.StateCallback()
 * onConfigured
 * onConfigureFailed
 ### CameraDevice.StateCallback
 * onOpened()
 * onDisConnected()
 * onError()
## CameraManager
 * getCameraIdList() - get available camera ID array
 * getCameraCharacteristics(cameraID) - get CameraCharacteristics
 * openCamera(camerID, CameraDevice.StateCallback, null) - open specific camera and assign callbacks
## CameraCharacteristics
## StreamConfigurationMap
## CaptureRequest.Builder
 * addTarget()
 * build()

## class MediaRecorder

## class TextureView
  * TextureView.SurfaceTextureListener - state listener of TextureView
  ** onSurfaceTextureAvailable
  ** onSurfaceTextureSizeChanged
  ** onSurfaceTextureDestroyed
  ** onSurfaceTextureUpdated
