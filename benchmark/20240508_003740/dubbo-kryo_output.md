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
# Warmup Iteration   1: 1.617 ops/ms
Iteration   1: 6.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.628 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.521 ops/ms
Iteration   1: 12.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.072 ops/ms


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
# Warmup Iteration   1: 5.266 ops/ms
Iteration   1: 12.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.575 ops/ms


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
# Warmup Iteration   1: 4.566 ops/ms
Iteration   1: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.225 ops/ms


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.070 ms/op
Iteration   1: 2.492 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.492 ms/op


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
# Warmup Iteration   1: 3.616 ±(99.9%) 0.049 ms/op
Iteration   1: 1.690 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.690 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.064 ms/op
Iteration   1: 2.101 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.101 ms/op


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.121 ms/op
Iteration   1: 3.287 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.287 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.120 ms/op
Iteration   1: 2.096 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   3.011 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  15.745 ms/op
                 createUser·p0.9999: 16.407 ms/op
                 createUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15286
  mean =      2.096 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 12803 
    [ 2.500,  3.750) = 2022 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     16.407 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 3.074 ±(99.9%) 0.082 ms/op
Iteration   1: 1.743 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.414 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.141 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   2.999 ms/op
                 existUser·p0.999:  15.182 ms/op
                 existUser·p0.9999: 16.588 ms/op
                 existUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18381
  mean =      1.743 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 894 
    [ 1.250,  2.500) = 16932 
    [ 2.500,  3.750) = 471 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.141 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      2.999 ms/op
     p(99.9000) =     15.182 ms/op
     p(99.9900) =     16.588 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.086 ms/op
Iteration   1: 2.357 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.269 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.411 ms/op
                 getUser·p0.9999: 14.967 ms/op
                 getUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13546
  mean =      2.357 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 9612 
    [ 2.500,  3.750) = 3557 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     11.411 ms/op
     p(99.9900) =     14.967 ms/op
     p(99.9990) =     15.466 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.157 ms/op
Iteration   1: 3.722 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8612
  mean =      3.722 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 492 
    [ 2.500,  3.750) = 4459 
    [ 3.750,  5.000) = 3224 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     15.385 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.628          ops/ms
ClientSimple.existUser                       thrpt         12.072          ops/ms
ClientSimple.getUser                         thrpt         12.575          ops/ms
ClientSimple.listUser                        thrpt          8.225          ops/ms
ClientSimple.createUser                       avgt          2.492           ms/op
ClientSimple.existUser                        avgt          1.690           ms/op
ClientSimple.getUser                          avgt          2.101           ms/op
ClientSimple.listUser                         avgt          3.287           ms/op
ClientSimple.createUser                     sample  15286   2.096 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.608           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.357           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.745           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.407           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.433           ms/op
ClientSimple.existUser                      sample  18381   1.743 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.414           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.647           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.141           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.999           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.182           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.588           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.712           ms/op
ClientSimple.getUser                        sample  13546   2.357 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.831           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.211           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.956           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.411           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.967           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.466           ms/op
ClientSimple.listUser                       sample   8612   3.722 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.470           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.658           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.022           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.152           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.286           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.385           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.385           ms/op

Benchmark result is saved to 1715128336271.json
