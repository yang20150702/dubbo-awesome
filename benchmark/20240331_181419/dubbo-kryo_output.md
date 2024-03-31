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
# Warmup Iteration   1: 1.487 ops/ms
Iteration   1: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.661 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.651 ops/ms
Iteration   1: 10.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.981 ops/ms


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
# Warmup Iteration   1: 4.534 ops/ms
Iteration   1: 13.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.101 ops/ms


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
# Warmup Iteration   1: 4.912 ops/ms
Iteration   1: 7.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.915 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.265 ±(99.9%) 0.134 ms/op
Iteration   1: 2.509 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.509 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.080 ms/op
Iteration   1: 2.196 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.196 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.057 ms/op
Iteration   1: 2.093 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.093 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.084 ms/op
Iteration   1: 3.409 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.409 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.110 ms/op
Iteration   1: 2.002 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   1.737 ms/op
                 createUser·p0.90:   2.507 ms/op
                 createUser·p0.95:   2.864 ms/op
                 createUser·p0.99:   7.001 ms/op
                 createUser·p0.999:  19.038 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16136
  mean =      2.002 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 515 
    [ 1.250,  2.500) = 13970 
    [ 2.500,  3.750) = 1144 
    [ 3.750,  5.000) = 223 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.864 ms/op
     p(99.0000) =      7.001 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.076 ms/op
Iteration   1: 1.839 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17396
  mean =      1.839 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 366 
    [ 1.250,  2.500) = 16540 
    [ 2.500,  3.750) = 363 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.112 ms/op
Iteration   1: 2.148 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   3.002 ms/op
                 getUser·p0.99:   5.817 ms/op
                 getUser·p0.999:  22.155 ms/op
                 getUser·p0.9999: 27.577 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14885
  mean =      2.148 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13043 
    [ 2.500,  5.000) = 1677 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      5.817 ms/op
     p(99.9000) =     22.155 ms/op
     p(99.9900) =     27.577 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.136 ms/op
Iteration   1: 3.557 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.069 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  12.683 ms/op
                 listUser·p0.9999: 13.091 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8983
  mean =      3.557 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 1255 
    [ 2.500,  3.750) = 4300 
    [ 3.750,  5.000) = 2936 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 135 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.069 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     12.683 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.661          ops/ms
ClientSimple.existUser                       thrpt         10.981          ops/ms
ClientSimple.getUser                         thrpt         13.101          ops/ms
ClientSimple.listUser                        thrpt          7.915          ops/ms
ClientSimple.createUser                       avgt          2.509           ms/op
ClientSimple.existUser                        avgt          2.196           ms/op
ClientSimple.getUser                          avgt          2.093           ms/op
ClientSimple.listUser                         avgt          3.409           ms/op
ClientSimple.createUser                     sample  16136   2.002 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.477           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.737           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.864           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.001           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.038           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.235           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.235           ms/op
ClientSimple.existUser                      sample  17396   1.839 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.742           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.138           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.940           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.235           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.235           ms/op
ClientSimple.getUser                        sample  14885   2.148 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.817           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.155           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.577           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.195           ms/op
ClientSimple.listUser                       sample   8983   3.557 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.856           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.069           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.127           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.683           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.091           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.091           ms/op

Benchmark result is saved to 1711908596967.json
