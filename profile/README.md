# GTA:V Multiplayer

## Code of Conduct

### Branching

Điều đầu tiên cần làm trước khi thực hiện bất kỳ thay đổi nào trên source code là tạo một branch mới cho những thay đổi đó. Mỗi branch đại diện duy nhất một công việc cần hoàn thành.

Đặt tên branch cần thể hiện được ý nghĩa được công việc gắn liền với branch đó, quy định cú pháp: `type/ticket/title`.

Ví dụ:

> - **feat/1/nametag** - `type` là `feat`, `1` là id ticket, `nametag` là title... ý nghĩa đây là branch triển khai tính năng nametag, giải quyết ticket số 1.
> - **fix/2/vehicle-bug** - `type` là `fix`, `2` là id ticket, `vehicle-bug` là title... ý nghĩa đây là branch sửa lỗi vehicle, giải quyết ticket số 2.
> - **wip/bomb** - `type` là `wip`, `bomb` là title... ý nghĩa đây là branch thử nghiệm tính năng đặt bom, có thể không được sử dụng trong tương lai, không giải quyết ticket nào.

Một số `type`: `feat`, `fix`, `wip`, `refactor`...

### Committing

Commit đánh dấu một phần công việc được hoàn thành, nội dung commit cần tuân theo quy định của [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
