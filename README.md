# AMD GPUs fan control daemon

Reads GPUs temperatures via hwmon sysfs periodically, finds max per-card and applies pwm setting interpolating user provided temp/speed matrix. Supports multiple cards.