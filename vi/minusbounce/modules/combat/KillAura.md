# KillAura

#### Tên thường gọi: Aura, Slient Aura, KA, TriggerBot, ....
#### Danh mục: Combat
#### Chức năng: Tự động tấn công tất cả thực thể đang ở xung quanh người chơi trong một phạm vi xác định.
#### Settings: 
![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/8ec7ebea-944e-44d1-8b86-605663cd2354)

- MaxCPS: CPS tối đa để tấn công mục tiêu.
- MinCPS: CPS tối thiểu để tấn công mục tiêu.
- HurtTime: Thời gian còn lại địch sẽ dính sát thương. Khi hurtTime của địch lớn hơn hurtTime client chỉ định thì không đánh.
- Range: Khoảng cách có thể tấn công.
- ThroughWallsRange: Khoảng cách có thể tấn công xuyên tường.
- RotationRange: Khoảng cách có thể xoay về đối thủ.
- Swing: Hiệu ứng kiếm. Có 3 mode:
  + Normal: Chạy hiệu ứng kiếm + gửi packet hiệu ứng.
  + Packet: Chỉ gửi packet hiệu ứng.
  + None: Không gửi hiệu ứng.
    ![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/b1a838f8-029a-4b67-a46c-01ff009ad752)

- Rotation: Chế độ xoay người chơi đến thực thể.
  + Vanilla: Xoay tự nhiên
  + NCP: Bypass NCP Anticheat
  + Grim: Bypass Grim Anticheat
  + Intave: Bypass Intave Anticheat 
  + None: Không xoay
    ![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/17f12d12-3f69-4054-b802-4655c48df015)

- Intave-RandomAmount: Lượng tốc độ xoay ngẫu nhiên với Rotation Intave.
- TurnSpeed: Tốc độ quay của người chơi đến mục tiêu.
- KeepRotationLength: Thời gian giữ rotation.
- Priority: Lựa chọn mục tiêu ưu tiên. Client sẽ chọn theo tiêu chí gần nhất như:
  + Health: Thấp máu nhất. ()
  + Distance: Gần khoảng cách mục tiêu nhất. ()
  + HurtResistantTime: Chống chịu yếu nhất. ()
  + Armor: Giáp yếu nhất. ()
  + HurtTime: Sắp bị dính sát thương đầu tiên. ()
    ![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/081db337-144a-42a5-830f-2f34ed5ea1c4)

- TargetMode: Chế độ đánh.
  + Single: Đánh đơn. ()
  + Switch: Đánh 1 hit 1 người. ()
  + Multi: Đánh nhiều người cùng lúc. ()
  ![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/916d8447-f620-40af-9005-9117f3297b00)

- FailSwing: Chạy swing bản legit.
- OnlyHitOnMouseToTarget: Chỉ hit khi chuột xoay vào thực thể.
- AutoBlock: Tự động chặn kiếm khi đang tấn công mục tiêu.
  + None: Không chặn. ()
  + AfterTick: Chặn tại Post Motion và bỏ chặn trước hit. ()
  + Vanilla: Chặn sau hit và bỏ chặn trước hit. ()
  + NewNCP: Bypass AutoBlock dành cho NoCheatPlus. ()
  + RightHold: Chuột phải block. ()
  + Swing: Chặn theo swing. ()
    ![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/29f2abf3-1b73-4848-9eb9-c3ad8386802e)

- InteractAutoBlock: AutoBlock dạng giao tiếp với người chơi (Giống như click chuột phải vào NPC).
- AutoBlock-Range: Phạm vi có thể autoblock.
- RayCast: Kiểm tra giữa người chơi và địch có bị chặn bởi người khác không. Nếu có, không đánh.
- SilentRotation: Xoay trong im lặng.
- MovementCorrection: Di chuyển theo góc quay:  
  + None: Không di chuyển
  + Normal: Di chuyển góc quay như bình thường
  + Strict: Rất nghiêm ngặt (Legit)
  ![image](https://github.com/n0td1n0kh0a/docs-cheating2/assets/152876934/2be74fa3-097b-4c67-88e4-2442f6ff02a4)

- Predict: Hitbox đoán góc xoay.
- PredictSize: Kích thước hitbox cần đoán góc xoay.
- Circle: Vẽ vòng tròn có thể đánh.
- Accuracy: Số cạnh vẽ hình tròn tương đối.
- Red, Green, Blue, Alpha: Màu của hình tròn (Circle).
