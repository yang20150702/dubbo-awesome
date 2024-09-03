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
# Warmup Iteration   1: 2.364 ops/ms
Iteration   1: 7.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.936 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.692 ops/ms
Iteration   1: 13.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.792 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 6.872 ops/ms
Iteration   1: 14.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.694 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.237 ops/ms
Iteration   1: 9.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.928 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.070 ms/op
Iteration   1: 2.242 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.242 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ±(99.9%) 0.053 ms/op
Iteration   1: 1.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.824 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ±(99.9%) 0.049 ms/op
Iteration   1: 1.842 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.842 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.110 ms/op
Iteration   1: 3.285 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.285 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.778 ±(99.9%) 0.126 ms/op
Iteration   1: 2.368 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.884 ms/op
                 createUser·p0.95:   3.233 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  16.744 ms/op
                 createUser·p0.9999: 17.589 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13514
  mean =      2.368 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 9361 
    [ 2.500,  3.750) = 3623 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.233 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     17.589 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.758 ±(99.9%) 0.060 ms/op
Iteration   1: 1.780 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   2.740 ms/op
                 existUser·p0.999:  26.149 ms/op
                 existUser·p0.9999: 26.693 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17970
  mean =      1.780 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17657 
    [ 2.500,  5.000) = 248 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      2.740 ms/op
     p(99.9000) =     26.149 ms/op
     p(99.9900) =     26.693 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.153 ±(99.9%) 0.072 ms/op
Iteration   1: 1.855 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.232 ms/op
                 getUser·p0.95:   2.408 ms/op
                 getUser·p0.99:   3.147 ms/op
                 getUser·p0.999:  10.879 ms/op
                 getUser·p0.9999: 11.396 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17376
  mean =      1.855 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 16691 
    [ 2.500,  3.750) = 487 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.147 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     11.396 ms/op
     p(99.9990) =     11.469 ms/op
     p(99.9999) =     11.469 ms/op
    p(100.0000) =     11.469 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ±(99.9%) 0.104 ms/op
Iteration   1: 2.950 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   2.740 ms/op
                 listUser·p0.90:   3.600 ms/op
                 listUser·p0.95:   3.805 ms/op
                 listUser·p0.99:   4.522 ms/op
                 listUser·p0.999:  27.825 ms/op
                 listUser·p0.9999: 28.475 ms/op
                 listUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10839
  mean =      2.950 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1695 
    [ 2.500,  5.000) = 9097 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     27.825 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.936          ops/ms
ClientSimple.existUser                       thrpt         13.792          ops/ms
ClientSimple.getUser                         thrpt         14.694          ops/ms
ClientSimple.listUser                        thrpt          9.928          ops/ms
ClientSimple.createUser                       avgt          2.242           ms/op
ClientSimple.existUser                        avgt          1.824           ms/op
ClientSimple.getUser                          avgt          1.842           ms/op
ClientSimple.listUser                         avgt          3.285           ms/op
ClientSimple.createUser                     sample  13514   2.368 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.421           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.233           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.585           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.744           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.589           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.727           ms/op
ClientSimple.existUser                      sample  17970   1.780 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.527           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.149           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.693           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.771           ms/op
ClientSimple.getUser                        sample  17376   1.855 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.021           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.232           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.147           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.879           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.396           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.469           ms/op
ClientSimple.listUser                       sample  10839   2.950 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.214           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.740           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.805           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.825           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.475           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.475           ms/op

Benchmark result is saved to 1725365962515.json
