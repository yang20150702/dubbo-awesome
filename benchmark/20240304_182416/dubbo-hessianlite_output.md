# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.452 ops/ms
Iteration   1: 5.166 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.166 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.164 ops/ms
Iteration   1: 13.696 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.696 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.283 ops/ms
Iteration   1: 7.589 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.589 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.937 ops/ms
Iteration   1: 3.844 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.844 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.989 ±(99.9%) 0.066 ms/op
Iteration   1: 3.398 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.398 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ±(99.9%) 0.048 ms/op
Iteration   1: 1.815 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.815 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.067 ms/op
Iteration   1: 3.010 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.010 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.321 ±(99.9%) 0.205 ms/op
Iteration   1: 9.305 ±(99.9%) 0.104 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.985 ±(99.9%) 0.111 ms/op
Iteration   1: 3.027 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   2.753 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.074 ms/op
                 createUser·p0.999:  7.486 ms/op
                 createUser·p0.9999: 8.812 ms/op
                 createUser·p1.00:   8.815 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10578
  mean =      3.027 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 90 
    [2.000, 2.500) = 1947 
    [2.500, 3.000) = 4496 
    [3.000, 3.500) = 1714 
    [3.500, 4.000) = 1300 
    [4.000, 4.500) = 737 
    [4.500, 5.000) = 137 
    [5.000, 5.500) = 17 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 33 
    [6.500, 7.000) = 40 
    [7.000, 7.500) = 33 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.074 ms/op
     p(99.9000) =      7.486 ms/op
     p(99.9900) =      8.812 ms/op
     p(99.9990) =      8.815 ms/op
     p(99.9999) =      8.815 ms/op
    p(100.0000) =      8.815 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.264 ±(99.9%) 0.086 ms/op
Iteration   1: 1.584 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   1.475 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   2.980 ms/op
                 existUser·p0.999:  26.673 ms/op
                 existUser·p0.9999: 27.392 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 20242
  mean =      1.584 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19667 
    [ 2.500,  5.000) = 505 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.475 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      2.980 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     27.392 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ±(99.9%) 0.114 ms/op
Iteration   1: 2.626 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  10.008 ms/op
                 getUser·p0.9999: 11.111 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12161
  mean =      2.626 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 5412 
    [ 2.500,  3.750) = 6310 
    [ 3.750,  5.000) = 317 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     10.008 ms/op
     p(99.9900) =     11.111 ms/op
     p(99.9990) =     11.125 ms/op
     p(99.9999) =     11.125 ms/op
    p(100.0000) =     11.125 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.803 ±(99.9%) 0.416 ms/op
Iteration   1: 7.813 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   7.496 ms/op
                 listUser·p0.90:   10.076 ms/op
                 listUser·p0.95:   10.981 ms/op
                 listUser·p0.99:   16.953 ms/op
                 listUser·p0.999:  22.271 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4095
  mean =      7.813 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 180 
    [ 5.000,  7.500) = 1869 
    [ 7.500, 10.000) = 1618 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      7.496 ms/op
     p(90.0000) =     10.076 ms/op
     p(95.0000) =     10.981 ms/op
     p(99.0000) =     16.953 ms/op
     p(99.9000) =     22.271 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.166          ops/ms
Client.existUser                       thrpt         13.696          ops/ms
Client.getUser                         thrpt          7.589          ops/ms
Client.listUser                        thrpt          3.844          ops/ms
Client.createUser                       avgt          3.398           ms/op
Client.existUser                        avgt          1.815           ms/op
Client.getUser                          avgt          3.010           ms/op
Client.listUser                         avgt          9.305           ms/op
Client.createUser                     sample  10578   3.027 ± 0.024   ms/op
Client.createUser:createUser·p0.00    sample          1.579           ms/op
Client.createUser:createUser·p0.50    sample          2.753           ms/op
Client.createUser:createUser·p0.90    sample          3.985           ms/op
Client.createUser:createUser·p0.95    sample          4.301           ms/op
Client.createUser:createUser·p0.99    sample          6.074           ms/op
Client.createUser:createUser·p0.999   sample          7.486           ms/op
Client.createUser:createUser·p0.9999  sample          8.812           ms/op
Client.createUser:createUser·p1.00    sample          8.815           ms/op
Client.existUser                      sample  20242   1.584 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.522           ms/op
Client.existUser:existUser·p0.50      sample          1.475           ms/op
Client.existUser:existUser·p0.90      sample          2.175           ms/op
Client.existUser:existUser·p0.95      sample          2.343           ms/op
Client.existUser:existUser·p0.99      sample          2.980           ms/op
Client.existUser:existUser·p0.999     sample         26.673           ms/op
Client.existUser:existUser·p0.9999    sample         27.392           ms/op
Client.existUser:existUser·p1.00      sample         27.492           ms/op
Client.getUser                        sample  12161   2.626 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.751           ms/op
Client.getUser:getUser·p0.50          sample          2.568           ms/op
Client.getUser:getUser·p0.90          sample          3.375           ms/op
Client.getUser:getUser·p0.95          sample          3.613           ms/op
Client.getUser:getUser·p0.99          sample          4.547           ms/op
Client.getUser:getUser·p0.999         sample         10.008           ms/op
Client.getUser:getUser·p0.9999        sample         11.111           ms/op
Client.getUser:getUser·p1.00          sample         11.125           ms/op
Client.listUser                       sample   4095   7.813 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          1.712           ms/op
Client.listUser:listUser·p0.50        sample          7.496           ms/op
Client.listUser:listUser·p0.90        sample         10.076           ms/op
Client.listUser:listUser·p0.95        sample         10.981           ms/op
Client.listUser:listUser·p0.99        sample         16.953           ms/op
Client.listUser:listUser·p0.999       sample         22.271           ms/op
Client.listUser:listUser·p0.9999      sample         24.248           ms/op
Client.listUser:listUser·p1.00        sample         24.248           ms/op
