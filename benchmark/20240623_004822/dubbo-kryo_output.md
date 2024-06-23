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
# Warmup Iteration   1: 1.694 ops/ms
Iteration   1: 7.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.517 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.052 ops/ms
Iteration   1: 12.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.310 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.260 ops/ms
Iteration   1: 14.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.269 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.876 ops/ms
Iteration   1: 8.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.263 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.074 ms/op
Iteration   1: 2.115 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ±(99.9%) 0.057 ms/op
Iteration   1: 1.834 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.834 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ±(99.9%) 0.049 ms/op
Iteration   1: 2.003 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.003 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.077 ms/op
Iteration   1: 2.979 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.979 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.075 ms/op
Iteration   1: 2.331 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   10.461 ms/op
                 createUser·p0.999:  28.909 ms/op
                 createUser·p0.9999: 29.515 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13781
  mean =      2.331 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9752 
    [ 2.500,  5.000) = 3814 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =     10.461 ms/op
     p(99.9000) =     28.909 ms/op
     p(99.9900) =     29.515 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.652 ±(99.9%) 0.063 ms/op
Iteration   1: 2.071 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.604 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   5.071 ms/op
                 existUser·p0.999:  15.098 ms/op
                 existUser·p0.9999: 15.590 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15462
  mean =      2.071 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 288 
    [ 1.250,  2.500) = 13177 
    [ 2.500,  3.750) = 1740 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 108 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.604 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =     15.098 ms/op
     p(99.9900) =     15.590 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.075 ms/op
Iteration   1: 1.951 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   4.597 ms/op
                 getUser·p0.999:  14.117 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16389
  mean =      1.951 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 635 
    [ 1.250,  2.500) = 14298 
    [ 2.500,  3.750) = 1150 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.597 ms/op
     p(99.9000) =     14.117 ms/op
     p(99.9900) =     14.303 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.115 ms/op
Iteration   1: 3.602 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   3.494 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   10.727 ms/op
                 listUser·p0.999:  27.658 ms/op
                 listUser·p0.9999: 28.541 ms/op
                 listUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8970
  mean =      3.602 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 944 
    [ 2.500,  5.000) = 7767 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =     10.727 ms/op
     p(99.9000) =     27.658 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.517          ops/ms
ClientSimple.existUser                       thrpt         12.310          ops/ms
ClientSimple.getUser                         thrpt         14.269          ops/ms
ClientSimple.listUser                        thrpt          8.263          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          1.834           ms/op
ClientSimple.getUser                          avgt          2.003           ms/op
ClientSimple.listUser                         avgt          2.979           ms/op
ClientSimple.createUser                     sample  13781   2.331 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.516           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.461           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.909           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.515           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.590           ms/op
ClientSimple.existUser                      sample  15462   2.071 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.692           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.604           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.071           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.098           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.590           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.679           ms/op
ClientSimple.getUser                        sample  16389   1.951 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.617           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.597           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.117           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.303           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.303           ms/op
ClientSimple.listUser                       sample   8970   3.602 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.906           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.494           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.727           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.658           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.541           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.541           ms/op

Benchmark result is saved to 1719103437434.json
