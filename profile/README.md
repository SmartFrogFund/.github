
# FrogFund: Decentralized Crowdfunding Platform

Leap to Your Dreams and Empower Your Journey to the Moon


## Description:
FrogFund envisions creating a decentralized, transparent, and fair crowdfunding platform that empowers creative projects and businesses to raise funds while enhancing investor trust and participation. We are committed to leveraging blockchain technology to provide a secure, fair, and efficient funding environment for global creative projects, enabling every creative individual to realize their dreams.

## Core Values:
1. **Transparency**:
   - FrogFund utilizes the immutability of blockchain to ensure that all fund movements and project progress are open and transparent, allowing investors to understand the use of funds and the latest project developments in real time.

2. **Fairness**:
   - Crowdfunding processes and fund distribution are automatically executed via smart contracts, avoiding human intervention and ensuring that all projects can compete in a fair environment.

3. **Community-Driven**:
   - By introducing frog-themed and social interaction elements, FrogFund creates an engaging, interactive, and vibrant crowdfunding community, stimulating investor enthusiasm and a sense of belonging.

4. **Innovation**:
   - We encourage and support innovative and groundbreaking projects, utilizing blockchain technology to provide more diverse funding and reward mechanisms, offering more possibilities for the realization of creative projects.

5. **Reliability**:
   - Investors can clearly see the progress of current investment projects, helping them to assess the reliability of projects.

## Frog Elements Implementation:
- **Project Display**: Our project mascot is a frog sitting on a rocket heading to the moon, echoing our project slogan, "Leap to Your Dreams and Empower Your Journey to the Moon."
- **Fundraising Rewards**: Both project creators and investors can earn Frog-related rewards, $CROAK memecoin.

## Business Process:
1. **Project Creation and Display**:
   - **Registration and Login**: Creative projects and businesses register accounts via wallet connection.
   - **Create Project**: Project initiators create crowdfunding projects on the platform, filling in detailed information and fundraising goals.
   - **Frog-Themed Design**: Project display pages are designed with frog themes to increase fun and attractiveness.

2. **Fundraising Process**:
   - **Investor Participation**: Investors support projects through the platform, choosing support amounts.
   - **Smart Contract Management**: Funds are stored in smart contracts to ensure security and transparency.
   - **Real-Time Progress**: Investors can view crowdfunding progress in real-time, including amounts raised and investor lists.

3. **Fund Distribution and Rewards**:
   - **Achieving Fundraising Goals**: When fundraising goals are met, the project enters the review stage, where investors review project progress and release funds. The project is divided into stages: 30%, 50%, 70%, and 100%. Project creators update project progress, and investors release the current stage funds after each review.
   - **Criteria for disbursement of funds**: All the investors for the current project will be allowed to review the progress of the project's current phase. If the number of approving investors is greater than or equal to 50% of the reviewers, the system will automatically settle the disbursement of funds for the current phase.
   - **Fund Distribution Formula**: When a project reaches its fundraising goal, investors can review the project progress and automatically release funds and distribute rewards based on the review results. After each review, funds are released according to the percentage of project progress, and rewards are distributed to project initiators and investors.

   For example, if the project's fundraising goal is 100 ETH:
   - \($ T $\) is the project's target amount.
   - \( $P_i$ \) is the progress percentage of stage \( $i$ \) expressed as a decimal (e.g., 30% is 0.3).
   - \( $A_i$ \) is the amount released at stage \($ i$ \).

   The formula is:
   \[
   $A_i = T \times (P_i - P_{i-1})$
   \]

   First stage:
   \[
   $A_1 = T \times P_1 = 100 \times 0.3 = 30 \text{ ETH}$
   \]

   Second stage:
   \[
   $A_2 = T \times (P_2 - P_1) = 100 \times (0.5 - 0.3) = 100 \times 0.2 = 20 \text{ ETH}$
   \]

   Third stage:
   \[
   $A_3 = T \times (P_3 - P_2) = 100 \times (0.7 - 0.5) = 100 \times 0.2 = 20 \text{ ETH}$
   \]

   Fourth stage:
   \[
   $A_4 = T \times (P_4 - P_3) = 100 \times (1 - 0.7) = 100 \times 0.3 = 30 \text{ ETH}$
   \]

   By calculating the differences, the amount to be released at each stage can be determined. The total sum of the amounts released at each stage is 100 ETH.

4. **Reward Distribution**: Upon successful review of each project stage, reward tokens like $CROAK memecoin are distributed to project creators and investors through smart contracts.

5. **Post-Crowdfunding Dynamic Follow-Up**:
   - **Project Updates Page**: Each project has an updates page where investors can view the latest progress and updates at any time.
   - **Notification System**: Investors can choose to receive notifications for project updates and listen to contract approval events.
   - **Progress Reports**: Project initiators periodically publish detailed progress reports, including financial status, project progress, and next steps.
   - **Community Interaction**: Investors can comment and suggest on the platform, interact with project initiators and other investors, forming an active community. (Future)

