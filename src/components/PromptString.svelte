<div class="prompt-string">
  <hr />
  <div class="top-prefix">
    <span class="left-curve">╭</span>
    <span class="emoji">🖥</span>
    <span class="path">~/esfox/github/io</span>
  </div>
  <div class="bottom-prefix">
    <span class="left-curve">╰$</span>
  </div>
</div>

<style lang="scss">
  .prompt-string {
    font-size: 13px;

    .left-curve {
      color: var(--yellow);
    }

    .top-prefix {
      display: flex;
      margin-top: 6px;
      height: 18px;
      margin-inline-start: 4px;

      .emoji {
        display: flex;
        align-items: center;
        background: var(--background);
        padding-inline-start: 2px;

        &::after {
          content: '';
          display: block;
          width: 0;
          height: 0;
          border-top: 9.5px solid var(--green);
          border-bottom: 9px solid var(--green);
          border-inline-start: 9px solid var(--background);
          margin-inline-start: 4px;
        }
      }

      .path {
        display: flex;
        color: var(--black);
        font-weight: 700;
        background: var(--green);
        padding-inline-start: 6px;

        &::after {
          content: '';
          display: block;
          width: 0;
          height: 0;
          border-top: 9px solid var(--background);
          border-bottom: 9.5px solid var(--background);
          border-inline-start: 9px solid var(--green);
          margin-inline-start: 4px;
        }
      }
    }

    .bottom-prefix {
      transform: translateY(-2px);
      margin-inline-start: 4px;
    }
  }
</style>
