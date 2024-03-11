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
# Warmup Iteration   1: 2.557 ops/ms
Iteration   1: 6.007 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.007 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.321 ops/ms
Iteration   1: 13.573 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.573 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ops/ms
Iteration   1: 8.654 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.654 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.441 ops/ms
Iteration   1: 3.673 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.673 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ±(99.9%) 0.070 ms/op
Iteration   1: 3.110 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.110 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.031 ms/op
Iteration   1: 1.740 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.740 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ±(99.9%) 0.057 ms/op
Iteration   1: 2.979 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.979 ms/op


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
# Warmup Iteration   1: 11.870 ±(99.9%) 0.248 ms/op
Iteration   1: 7.592 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.592 ms/op


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
# Warmup Iteration   1: 5.384 ±(99.9%) 0.135 ms/op
Iteration   1: 3.291 ±(99.9%) 0.079 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   11.492 ms/op
                 createUser·p0.999:  33.751 ms/op
                 createUser·p0.9999: 34.931 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9719
  mean =      3.291 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1609 
    [ 2.500,  5.000) = 7661 
    [ 5.000,  7.500) = 234 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =     11.492 ms/op
     p(99.9000) =     33.751 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.367 ±(99.9%) 0.076 ms/op
Iteration   1: 2.079 ±(99.9%) 0.079 ms/op
                 existUser·p0.00:   0.366 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.814 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  64.618 ms/op
                 existUser·p0.9999: 68.781 ms/op
                 existUser·p1.00:   69.206 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15400
  mean =      2.079 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15222 
    [ 5.000, 10.000) = 125 
    [10.000, 15.000) = 7 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 11 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     64.618 ms/op
     p(99.9900) =     68.781 ms/op
     p(99.9990) =     69.206 ms/op
     p(99.9999) =     69.206 ms/op
    p(100.0000) =     69.206 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.096 ms/op
Iteration   1: 3.188 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.946 ms/op
                 getUser·p0.95:   4.568 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  15.004 ms/op
                 getUser·p0.9999: 16.564 ms/op
                 getUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10046
  mean =      3.188 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1986 
    [ 2.500,  3.750) = 6517 
    [ 3.750,  5.000) = 1285 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.946 ms/op
     p(95.0000) =      4.568 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     15.004 ms/op
     p(99.9900) =     16.564 ms/op
     p(99.9990) =     16.564 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.865 ±(99.9%) 0.439 ms/op
Iteration   1: 8.949 ±(99.9%) 0.142 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   8.651 ms/op
                 listUser·p0.90:   11.469 ms/op
                 listUser·p0.95:   12.661 ms/op
                 listUser·p0.99:   20.991 ms/op
                 listUser·p0.999:  29.661 ms/op
                 listUser·p0.9999: 32.342 ms/op
                 listUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3704
  mean =      8.949 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 87 
    [ 5.000,  7.500) = 960 
    [ 7.500, 10.000) = 1699 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.830 ms/op
     p(50.0000) =      8.651 ms/op
     p(90.0000) =     11.469 ms/op
     p(95.0000) =     12.661 ms/op
     p(99.0000) =     20.991 ms/op
     p(99.9000) =     29.661 ms/op
     p(99.9900) =     32.342 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.007          ops/ms
Client.existUser                       thrpt         13.573          ops/ms
Client.getUser                         thrpt          8.654          ops/ms
Client.listUser                        thrpt          3.673          ops/ms
Client.createUser                       avgt          3.110           ms/op
Client.existUser                        avgt          1.740           ms/op
Client.getUser                          avgt          2.979           ms/op
Client.listUser                         avgt          7.592           ms/op
Client.createUser                     sample   9719   3.291 ± 0.079   ms/op
Client.createUser:createUser·p0.00    sample          0.905           ms/op
Client.createUser:createUser·p0.50    sample          2.839           ms/op
Client.createUser:createUser·p0.90    sample          4.055           ms/op
Client.createUser:createUser·p0.95    sample          4.801           ms/op
Client.createUser:createUser·p0.99    sample         11.492           ms/op
Client.createUser:createUser·p0.999   sample         33.751           ms/op
Client.createUser:createUser·p0.9999  sample         34.931           ms/op
Client.createUser:createUser·p1.00    sample         34.931           ms/op
Client.existUser                      sample  15400   2.079 ± 0.079   ms/op
Client.existUser:existUser·p0.00      sample          0.366           ms/op
Client.existUser:existUser·p0.50      sample          1.876           ms/op
Client.existUser:existUser·p0.90      sample          2.568           ms/op
Client.existUser:existUser·p0.95      sample          2.814           ms/op
Client.existUser:existUser·p0.99      sample          5.120           ms/op
Client.existUser:existUser·p0.999     sample         64.618           ms/op
Client.existUser:existUser·p0.9999    sample         68.781           ms/op
Client.existUser:existUser·p1.00      sample         69.206           ms/op
Client.getUser                        sample  10046   3.188 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.835           ms/op
Client.getUser:getUser·p0.50          sample          3.117           ms/op
Client.getUser:getUser·p0.90          sample          3.946           ms/op
Client.getUser:getUser·p0.95          sample          4.568           ms/op
Client.getUser:getUser·p0.99          sample          6.332           ms/op
Client.getUser:getUser·p0.999         sample         15.004           ms/op
Client.getUser:getUser·p0.9999        sample         16.564           ms/op
Client.getUser:getUser·p1.00          sample         16.564           ms/op
Client.listUser                       sample   3704   8.949 ± 0.142   ms/op
Client.listUser:listUser·p0.00        sample          2.830           ms/op
Client.listUser:listUser·p0.50        sample          8.651           ms/op
Client.listUser:listUser·p0.90        sample         11.469           ms/op
Client.listUser:listUser·p0.95        sample         12.661           ms/op
Client.listUser:listUser·p0.99        sample         20.991           ms/op
Client.listUser:listUser·p0.999       sample         29.661           ms/op
Client.listUser:listUser·p0.9999      sample         32.342           ms/op
Client.listUser:listUser·p1.00        sample         32.342           ms/op
