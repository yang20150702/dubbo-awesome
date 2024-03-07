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
# Warmup Iteration   1: 1.973 ops/ms
Iteration   1: 5.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.395 ops/ms


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
# Warmup Iteration   1: 5.539 ops/ms
Iteration   1: 13.225 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.225 ops/ms


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
# Warmup Iteration   1: 3.921 ops/ms
Iteration   1: 7.547 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.547 ops/ms


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
# Warmup Iteration   1: 1.958 ops/ms
Iteration   1: 3.264 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.264 ops/ms


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
# Warmup Iteration   1: 5.712 ±(99.9%) 0.076 ms/op
Iteration   1: 3.235 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.235 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.036 ms/op
Iteration   1: 2.118 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.118 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.068 ms/op
Iteration   1: 3.535 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.535 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.755 ±(99.9%) 0.206 ms/op
Iteration   1: 10.056 ±(99.9%) 0.168 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.056 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.124 ms/op
Iteration   1: 3.046 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   8.831 ms/op
                 createUser·p0.999:  12.805 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10465
  mean =      3.046 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 2930 
    [ 2.500,  3.750) = 6576 
    [ 3.750,  5.000) = 605 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     12.805 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.071 ms/op
Iteration   1: 1.882 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.294 ms/op
                 existUser·p0.999:  24.967 ms/op
                 existUser·p0.9999: 25.447 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17073
  mean =      1.882 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16124 
    [ 2.500,  5.000) = 848 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.294 ms/op
     p(99.9000) =     24.967 ms/op
     p(99.9900) =     25.447 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 5.459 ±(99.9%) 0.150 ms/op
Iteration   1: 2.955 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   2.839 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 9.858 ms/op
                 getUser·p1.00:   9.978 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10925
  mean =      2.955 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 22 
    [ 1.500,  2.000) = 268 
    [ 2.000,  2.500) = 1992 
    [ 2.500,  3.000) = 4504 
    [ 3.000,  3.500) = 2611 
    [ 3.500,  4.000) = 799 
    [ 4.000,  4.500) = 402 
    [ 4.500,  5.000) = 194 
    [ 5.000,  5.500) = 37 
    [ 5.500,  6.000) = 14 
    [ 6.000,  6.500) = 12 
    [ 6.500,  7.000) = 25 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 32 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 12 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =      9.858 ms/op
     p(99.9990) =      9.978 ms/op
     p(99.9999) =      9.978 ms/op
    p(100.0000) =      9.978 ms/op


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
# Warmup Iteration   1: 14.792 ±(99.9%) 0.541 ms/op
Iteration   1: 8.740 ±(99.9%) 0.160 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   8.438 ms/op
                 listUser·p0.90:   11.420 ms/op
                 listUser·p0.95:   12.589 ms/op
                 listUser·p0.99:   20.677 ms/op
                 listUser·p0.999:  31.277 ms/op
                 listUser·p0.9999: 31.687 ms/op
                 listUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3652
  mean =      8.740 ±(99.9%) 0.160 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 153 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 1627 
    [10.000, 12.500) = 659 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      8.438 ms/op
     p(90.0000) =     11.420 ms/op
     p(95.0000) =     12.589 ms/op
     p(99.0000) =     20.677 ms/op
     p(99.9000) =     31.277 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.395          ops/ms
Client.existUser                       thrpt         13.225          ops/ms
Client.getUser                         thrpt          7.547          ops/ms
Client.listUser                        thrpt          3.264          ops/ms
Client.createUser                       avgt          3.235           ms/op
Client.existUser                        avgt          2.118           ms/op
Client.getUser                          avgt          3.535           ms/op
Client.listUser                         avgt         10.056           ms/op
Client.createUser                     sample  10465   3.046 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.472           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.682           ms/op
Client.createUser:createUser·p0.95    sample          4.227           ms/op
Client.createUser:createUser·p0.99    sample          8.831           ms/op
Client.createUser:createUser·p0.999   sample         12.805           ms/op
Client.createUser:createUser·p0.9999  sample         12.878           ms/op
Client.createUser:createUser·p1.00    sample         12.878           ms/op
Client.existUser                      sample  17073   1.882 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.431           ms/op
Client.existUser:existUser·p0.50      sample          1.743           ms/op
Client.existUser:existUser·p0.90      sample          2.343           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          3.294           ms/op
Client.existUser:existUser·p0.999     sample         24.967           ms/op
Client.existUser:existUser·p0.9999    sample         25.447           ms/op
Client.existUser:existUser·p1.00      sample         25.494           ms/op
Client.getUser                        sample  10925   2.955 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.159           ms/op
Client.getUser:getUser·p0.50          sample          2.839           ms/op
Client.getUser:getUser·p0.90          sample          3.744           ms/op
Client.getUser:getUser·p0.95          sample          4.178           ms/op
Client.getUser:getUser·p0.99          sample          5.194           ms/op
Client.getUser:getUser·p0.999         sample          8.536           ms/op
Client.getUser:getUser·p0.9999        sample          9.858           ms/op
Client.getUser:getUser·p1.00          sample          9.978           ms/op
Client.listUser                       sample   3652   8.740 ± 0.160   ms/op
Client.listUser:listUser·p0.00        sample          1.665           ms/op
Client.listUser:listUser·p0.50        sample          8.438           ms/op
Client.listUser:listUser·p0.90        sample         11.420           ms/op
Client.listUser:listUser·p0.95        sample         12.589           ms/op
Client.listUser:listUser·p0.99        sample         20.677           ms/op
Client.listUser:listUser·p0.999       sample         31.277           ms/op
Client.listUser:listUser·p0.9999      sample         31.687           ms/op
Client.listUser:listUser·p1.00        sample         31.687           ms/op
