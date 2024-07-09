# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.710 ops/ms
Iteration   1: 7.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.238 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.078 ops/ms
Iteration   1: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.528 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.538 ops/ms
Iteration   1: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.427 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ops/ms
Iteration   1: 8.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.304 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.063 ms/op
Iteration   1: 2.176 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.498 ±(99.9%) 0.086 ms/op
Iteration   1: 2.207 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ±(99.9%) 0.063 ms/op
Iteration   1: 2.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.075 ms/op
Iteration   1: 3.612 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.612 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ±(99.9%) 0.102 ms/op
Iteration   1: 2.383 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.892 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   7.781 ms/op
                 createUser·p0.999:  27.492 ms/op
                 createUser·p0.9999: 28.092 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13402
  mean =      2.383 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9873 
    [ 2.500,  5.000) = 3248 
    [ 5.000,  7.500) = 141 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      7.781 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     28.092 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.265 ±(99.9%) 0.115 ms/op
Iteration   1: 2.136 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.342 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  26.083 ms/op
                 existUser·p0.9999: 26.431 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15280
  mean =      2.136 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13557 
    [ 2.500,  5.000) = 1454 
    [ 5.000,  7.500) = 168 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.431 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ±(99.9%) 0.095 ms/op
Iteration   1: 1.984 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   3.755 ms/op
                 getUser·p0.999:  12.796 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16124
  mean =      1.984 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 14529 
    [ 2.500,  3.750) = 1392 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.755 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.334 ±(99.9%) 0.114 ms/op
Iteration   1: 3.637 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  26.107 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8789
  mean =      3.637 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 657 
    [ 2.500,  5.000) = 7743 
    [ 5.000,  7.500) = 320 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     26.107 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.238          ops/ms
ClientSimple.existUser                       thrpt         10.528          ops/ms
ClientSimple.getUser                         thrpt         10.427          ops/ms
ClientSimple.listUser                        thrpt          8.304          ops/ms
ClientSimple.createUser                       avgt          2.176           ms/op
ClientSimple.existUser                        avgt          2.207           ms/op
ClientSimple.getUser                          avgt          2.032           ms/op
ClientSimple.listUser                         avgt          3.612           ms/op
ClientSimple.createUser                     sample  13402   2.383 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.731           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.240           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.781           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.492           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.092           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.148           ms/op
ClientSimple.existUser                      sample  15280   2.136 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.342           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.849           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.083           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.431           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.673           ms/op
ClientSimple.getUser                        sample  16124   1.984 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.534           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.755           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.796           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.730           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.730           ms/op
ClientSimple.listUser                       sample   8789   3.637 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.198           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.775           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.107           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.706           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.706           ms/op

Benchmark result is saved to 1720485713598.json
