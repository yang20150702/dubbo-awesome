# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.080 ops/ms
Iteration   1: 8.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.644 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.456 ops/ms
Iteration   1: 14.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.012 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 7.005 ops/ms
Iteration   1: 14.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.321 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.711 ops/ms
Iteration   1: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.673 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.168 ms/op
Iteration   1: 1.972 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.820 ±(99.9%) 0.079 ms/op
Iteration   1: 1.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.551 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 2.797 ±(99.9%) 0.043 ms/op
Iteration   1: 1.846 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.846 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.098 ms/op
Iteration   1: 3.326 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.326 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ±(99.9%) 0.099 ms/op
Iteration   1: 2.018 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   1.878 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.666 ms/op
                 createUser·p0.99:   5.514 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16185
  mean =      2.018 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14700 
    [ 2.500,  5.000) = 1296 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      5.514 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.673 ±(99.9%) 0.062 ms/op
Iteration   1: 1.539 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.284 ms/op
                 existUser·p0.50:   1.503 ms/op
                 existUser·p0.90:   1.853 ms/op
                 existUser·p0.95:   2.048 ms/op
                 existUser·p0.99:   2.395 ms/op
                 existUser·p0.999:  5.769 ms/op
                 existUser·p0.9999: 6.466 ms/op
                 existUser·p1.00:   6.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 20735
  mean =      1.539 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 48 
    [0.500, 1.000) = 507 
    [1.000, 1.500) = 9662 
    [1.500, 2.000) = 9289 
    [2.000, 2.500) = 1048 
    [2.500, 3.000) = 85 
    [3.000, 3.500) = 35 
    [3.500, 4.000) = 23 
    [4.000, 4.500) = 2 
    [4.500, 5.000) = 12 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      1.503 ms/op
     p(90.0000) =      1.853 ms/op
     p(95.0000) =      2.048 ms/op
     p(99.0000) =      2.395 ms/op
     p(99.9000) =      5.769 ms/op
     p(99.9900) =      6.466 ms/op
     p(99.9990) =      6.808 ms/op
     p(99.9999) =      6.808 ms/op
    p(100.0000) =      6.808 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ±(99.9%) 0.080 ms/op
Iteration   1: 1.740 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   1.636 ms/op
                 getUser·p0.90:   2.204 ms/op
                 getUser·p0.95:   2.437 ms/op
                 getUser·p0.99:   2.961 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 11.267 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18364
  mean =      1.740 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 17419 
    [ 2.500,  3.750) = 708 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      1.636 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      2.961 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     11.267 ms/op
     p(99.9990) =     11.321 ms/op
     p(99.9999) =     11.321 ms/op
    p(100.0000) =     11.321 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ±(99.9%) 0.098 ms/op
Iteration   1: 3.036 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.658 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  27.427 ms/op
                 listUser·p0.9999: 28.134 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10517
  mean =      3.036 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4630 
    [ 2.500,  5.000) = 5619 
    [ 5.000,  7.500) = 183 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     27.427 ms/op
     p(99.9900) =     28.134 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.644          ops/ms
ClientSimple.existUser                       thrpt         14.012          ops/ms
ClientSimple.getUser                         thrpt         14.321          ops/ms
ClientSimple.listUser                        thrpt          9.673          ops/ms
ClientSimple.createUser                       avgt          1.972           ms/op
ClientSimple.existUser                        avgt          1.551           ms/op
ClientSimple.getUser                          avgt          1.846           ms/op
ClientSimple.listUser                         avgt          3.326           ms/op
ClientSimple.createUser                     sample  16185   2.018 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.675           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.878           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.666           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.514           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.331           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.626           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.626           ms/op
ClientSimple.existUser                      sample  20735   1.539 ± 0.008   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.284           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.503           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.395           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.769           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.466           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.808           ms/op
ClientSimple.getUser                        sample  18364   1.740 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.797           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.636           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.043           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.267           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.321           ms/op
ClientSimple.listUser                       sample  10517   3.036 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.833           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.658           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.873           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.427           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.134           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.148           ms/op

Benchmark result is saved to 1723119447542.json
