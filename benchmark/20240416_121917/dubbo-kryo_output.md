# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.716 ops/ms
Iteration   1: 4.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.876 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ops/ms
Iteration   1: 9.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.407 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ops/ms
Iteration   1: 9.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.955 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ops/ms
Iteration   1: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.282 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.610 ±(99.9%) 0.121 ms/op
Iteration   1: 2.662 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.662 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ±(99.9%) 0.070 ms/op
Iteration   1: 2.087 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.087 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.083 ms/op
Iteration   1: 2.298 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ±(99.9%) 0.109 ms/op
Iteration   1: 3.894 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.894 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.108 ms/op
Iteration   1: 2.510 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   4.205 ms/op
                 createUser·p0.99:   12.459 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 22.938 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12753
  mean =      2.510 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9559 
    [ 2.500,  5.000) = 2685 
    [ 5.000,  7.500) = 151 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      4.205 ms/op
     p(99.0000) =     12.459 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.097 ms/op
Iteration   1: 2.229 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.048 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.505 ms/op
                 existUser·p0.999:  14.346 ms/op
                 existUser·p0.9999: 14.699 ms/op
                 existUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14412
  mean =      2.229 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 10629 
    [ 2.500,  3.750) = 3206 
    [ 3.750,  5.000) = 297 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      3.178 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.505 ms/op
     p(99.9000) =     14.346 ms/op
     p(99.9900) =     14.699 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.669 ±(99.9%) 0.102 ms/op
Iteration   1: 2.013 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.351 ms/op
                 getUser·p0.50:   1.933 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  11.683 ms/op
                 getUser·p0.9999: 12.714 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15919
  mean =      2.013 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 416 
    [ 1.250,  2.500) = 13721 
    [ 2.500,  3.750) = 1614 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =     11.683 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.036 ±(99.9%) 0.169 ms/op
Iteration   1: 3.618 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.878 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8830
  mean =      3.618 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 676 
    [ 2.500,  5.000) = 7819 
    [ 5.000,  7.500) = 242 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.878 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.876          ops/ms
ClientSimple.existUser                       thrpt          9.407          ops/ms
ClientSimple.getUser                         thrpt          9.955          ops/ms
ClientSimple.listUser                        thrpt          8.282          ops/ms
ClientSimple.createUser                       avgt          2.662           ms/op
ClientSimple.existUser                        avgt          2.087           ms/op
ClientSimple.getUser                          avgt          2.298           ms/op
ClientSimple.listUser                         avgt          3.894           ms/op
ClientSimple.createUser                     sample  12753   2.510 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.113           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.205           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.459           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.184           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.938           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.938           ms/op
ClientSimple.existUser                      sample  14412   2.229 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.730           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.90      sample          3.178           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.505           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.346           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.699           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.778           ms/op
ClientSimple.getUser                        sample  15919   2.013 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.351           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.933           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.854           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.683           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.714           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.714           ms/op
ClientSimple.listUser                       sample   8830   3.618 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.135           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.878           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.537           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.317           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.447           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.447           ms/op

Benchmark result is saved to 1713269693364.json
