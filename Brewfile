# frozen_string_literal: true

tap "github/bootstrap"

cask "docker" unless system "which docker"
cask "ngrok"

brew "tmux"
brew "overmind"
brew "nginx", restart_service: :changed
brew "postgresql@13"
brew "terminal-notifier"
brew "yarn"
