# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.250 ops/ms
Iteration   1: 5.736 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.736 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.536 ops/ms
Iteration   1: 12.957 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.957 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ops/ms
Iteration   1: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.697 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.169 ops/ms
Iteration   1: 4.043 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.043 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.562 ±(99.9%) 0.093 ms/op
Iteration   1: 3.244 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.244 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.066 ±(99.9%) 0.032 ms/op
Iteration   1: 1.782 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.782 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.058 ms/op
Iteration   1: 3.325 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.325 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.877 ±(99.9%) 0.174 ms/op
Iteration   1: 8.267 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.267 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.936 ±(99.9%) 0.129 ms/op
Iteration   1: 2.978 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.539 ms/op
                 createUser·p0.999:  15.516 ms/op
                 createUser·p0.9999: 15.750 ms/op
                 createUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10773
  mean =      2.978 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2428 
    [ 2.500,  3.750) = 7407 
    [ 3.750,  5.000) = 740 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.539 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     15.750 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.172 ±(99.9%) 0.083 ms/op
Iteration   1: 1.779 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   1.630 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.159 ms/op
                 existUser·p0.999:  24.314 ms/op
                 existUser·p0.9999: 24.950 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17973
  mean =      1.779 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17416 
    [ 2.500,  5.000) = 519 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      1.630 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.159 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     24.950 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.824 ±(99.9%) 0.137 ms/op
Iteration   1: 3.157 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.398 ms/op
                 getUser·p0.999:  9.745 ms/op
                 getUser·p0.9999: 10.401 ms/op
                 getUser·p1.00:   10.404 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10200
  mean =      3.157 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 253 
    [ 2.000,  3.000) = 4400 
    [ 3.000,  4.000) = 4531 
    [ 4.000,  5.000) = 828 
    [ 5.000,  6.000) = 127 
    [ 6.000,  7.000) = 14 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 7 
    [ 9.000, 10.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.398 ms/op
     p(99.9000) =      9.745 ms/op
     p(99.9900) =     10.401 ms/op
     p(99.9990) =     10.404 ms/op
     p(99.9999) =     10.404 ms/op
    p(100.0000) =     10.404 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.861 ±(99.9%) 0.481 ms/op
Iteration   1: 7.145 ±(99.9%) 0.081 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   6.955 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   12.139 ms/op
                 listUser·p0.999:  18.469 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4590
  mean =      7.145 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 211 
    [ 5.000,  7.500) = 2815 
    [ 7.500, 10.000) = 1401 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.818 ms/op
     p(50.0000) =      6.955 ms/op
     p(90.0000) =      8.962 ms/op
     p(95.0000) =      9.601 ms/op
     p(99.0000) =     12.139 ms/op
     p(99.9000) =     18.469 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.736          ops/ms
Client.existUser                       thrpt         12.957          ops/ms
Client.getUser                         thrpt          7.697          ops/ms
Client.listUser                        thrpt          4.043          ops/ms
Client.createUser                       avgt          3.244           ms/op
Client.existUser                        avgt          1.782           ms/op
Client.getUser                          avgt          3.325           ms/op
Client.listUser                         avgt          8.267           ms/op
Client.createUser                     sample  10773   2.978 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          0.964           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.637           ms/op
Client.createUser:createUser·p0.95    sample          4.194           ms/op
Client.createUser:createUser·p0.99    sample          6.539           ms/op
Client.createUser:createUser·p0.999   sample         15.516           ms/op
Client.createUser:createUser·p0.9999  sample         15.750           ms/op
Client.createUser:createUser·p1.00    sample         15.761           ms/op
Client.existUser                      sample  17973   1.779 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.745           ms/op
Client.existUser:existUser·p0.50      sample          1.630           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.396           ms/op
Client.existUser:existUser·p0.99      sample          3.159           ms/op
Client.existUser:existUser·p0.999     sample         24.314           ms/op
Client.existUser:existUser·p0.9999    sample         24.950           ms/op
Client.existUser:existUser·p1.00      sample         25.133           ms/op
Client.getUser                        sample  10200   3.157 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.726           ms/op
Client.getUser:getUser·p0.50          sample          3.092           ms/op
Client.getUser:getUser·p0.90          sample          3.994           ms/op
Client.getUser:getUser·p0.95          sample          4.358           ms/op
Client.getUser:getUser·p0.99          sample          5.398           ms/op
Client.getUser:getUser·p0.999         sample          9.745           ms/op
Client.getUser:getUser·p0.9999        sample         10.401           ms/op
Client.getUser:getUser·p1.00          sample         10.404           ms/op
Client.listUser                       sample   4590   7.145 ± 0.081   ms/op
Client.listUser:listUser·p0.00        sample          2.818           ms/op
Client.listUser:listUser·p0.50        sample          6.955           ms/op
Client.listUser:listUser·p0.90        sample          8.962           ms/op
Client.listUser:listUser·p0.95        sample          9.601           ms/op
Client.listUser:listUser·p0.99        sample         12.139           ms/op
Client.listUser:listUser·p0.999       sample         18.469           ms/op
Client.listUser:listUser·p0.9999      sample         20.349           ms/op
Client.listUser:listUser·p1.00        sample         20.349           ms/op
