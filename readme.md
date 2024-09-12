class Getfilesize < Formula
  desc "Encrypt / Decrypt file"
  homepage "https://github.com/jianshangquan/file_encrypt.git"
  url "https://github.com/jianshangquan/file_encrypt/releases/download/v1/file-encrypt.tar.gz"
  sha256 "ea94d460dee92bb77423058790c23078337ec548b3f2f8b355812bda0527be27"
  license "MIT"
  version "1.0.0"

  def install
    bin.install "file-decrypt"
  end
end