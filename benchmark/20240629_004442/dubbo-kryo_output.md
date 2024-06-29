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
# Warmup Iteration   1: 1.826 ops/ms
Iteration   1: 6.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.817 ops/ms


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
# Warmup Iteration   1: 5.658 ops/ms
Iteration   1: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.543 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.379 ops/ms
Iteration   1: 12.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.395 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ops/ms
Iteration   1: 8.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.722 ops/ms


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.068 ms/op
Iteration   1: 2.219 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.219 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.052 ms/op
Iteration   1: 1.805 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.805 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.063 ms/op
Iteration   1: 1.981 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.981 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.110 ms/op
Iteration   1: 3.253 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.253 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.469 ±(99.9%) 0.086 ms/op
Iteration   1: 2.115 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   4.896 ms/op
                 createUser·p0.999:  14.727 ms/op
                 createUser·p0.9999: 15.449 ms/op
                 createUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15122
  mean =      2.115 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 13071 
    [ 2.500,  3.750) = 1702 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      4.896 ms/op
     p(99.9000) =     14.727 ms/op
     p(99.9900) =     15.449 ms/op
     p(99.9990) =     15.483 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 2.895 ±(99.9%) 0.073 ms/op
Iteration   1: 1.835 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.338 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  22.610 ms/op
                 existUser·p0.9999: 24.477 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17505
  mean =      1.835 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16909 
    [ 2.500,  5.000) = 446 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.338 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     24.477 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.073 ms/op
Iteration   1: 2.187 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.282 ms/op
                 getUser·p0.50:   2.138 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  11.770 ms/op
                 getUser·p0.9999: 11.956 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14621
  mean =      2.187 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 376 
    [ 1.250,  2.500) = 10990 
    [ 2.500,  3.750) = 3051 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     11.770 ms/op
     p(99.9900) =     11.956 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.165 ms/op
Iteration   1: 3.019 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.822 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   5.326 ms/op
                 listUser·p0.999:  6.884 ms/op
                 listUser·p0.9999: 7.150 ms/op
                 listUser·p1.00:   7.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10689
  mean =      3.019 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 77 
    [2.000, 2.500) = 1451 
    [2.500, 3.000) = 5417 
    [3.000, 3.500) = 1586 
    [3.500, 4.000) = 1279 
    [4.000, 4.500) = 526 
    [4.500, 5.000) = 154 
    [5.000, 5.500) = 110 
    [5.500, 6.000) = 17 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 21 
    [7.000, 7.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.326 ms/op
     p(99.9000) =      6.884 ms/op
     p(99.9900) =      7.150 ms/op
     p(99.9990) =      7.152 ms/op
     p(99.9999) =      7.152 ms/op
    p(100.0000) =      7.152 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.817          ops/ms
ClientSimple.existUser                       thrpt         12.543          ops/ms
ClientSimple.getUser                         thrpt         12.395          ops/ms
ClientSimple.listUser                        thrpt          8.722          ops/ms
ClientSimple.createUser                       avgt          2.219           ms/op
ClientSimple.existUser                        avgt          1.805           ms/op
ClientSimple.getUser                          avgt          1.981           ms/op
ClientSimple.listUser                         avgt          3.253           ms/op
ClientSimple.createUser                     sample  15122   2.115 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.642           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.896           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.727           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.449           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.483           ms/op
ClientSimple.existUser                      sample  17505   1.835 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.658           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.338           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.817           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.610           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.477           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.952           ms/op
ClientSimple.getUser                        sample  14621   2.187 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.282           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.138           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.117           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.448           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.770           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.956           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.009           ms/op
ClientSimple.listUser                       sample  10689   3.019 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.878           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.908           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.326           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.884           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.150           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.152           ms/op

Benchmark result is saved to 1719621628344.json
