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
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.810 ops/ms


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
# Warmup Iteration   1: 6.259 ops/ms
Iteration   1: 12.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.531 ops/ms


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
# Warmup Iteration   1: 5.365 ops/ms
Iteration   1: 13.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.633 ops/ms


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
# Warmup Iteration   1: 4.461 ops/ms
Iteration   1: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.554 ops/ms


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.076 ms/op
Iteration   1: 2.111 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.111 ms/op


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
# Warmup Iteration   1: 3.017 ±(99.9%) 0.043 ms/op
Iteration   1: 1.807 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.065 ms/op
Iteration   1: 2.136 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.136 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.095 ms/op
Iteration   1: 3.585 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.585 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.109 ms/op
Iteration   1: 2.140 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   1.829 ms/op
                 createUser·p0.90:   2.744 ms/op
                 createUser·p0.95:   3.059 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  28.869 ms/op
                 createUser·p0.9999: 30.296 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14961
  mean =      2.140 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12636 
    [ 2.500,  5.000) = 2128 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.059 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     28.869 ms/op
     p(99.9900) =     30.296 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 2.931 ±(99.9%) 0.069 ms/op
Iteration   1: 1.899 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.636 ms/op
                 existUser·p0.999:  10.278 ms/op
                 existUser·p0.9999: 10.884 ms/op
                 existUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16853
  mean =      1.899 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 15977 
    [ 2.500,  3.750) = 450 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.636 ms/op
     p(99.9000) =     10.278 ms/op
     p(99.9900) =     10.884 ms/op
     p(99.9990) =     10.895 ms/op
     p(99.9999) =     10.895 ms/op
    p(100.0000) =     10.895 ms/op


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
# Warmup Iteration   1: 3.402 ±(99.9%) 0.093 ms/op
Iteration   1: 1.958 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.401 ms/op
                 getUser·p0.95:   2.621 ms/op
                 getUser·p0.99:   3.346 ms/op
                 getUser·p0.999:  11.027 ms/op
                 getUser·p0.9999: 11.497 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16318
  mean =      1.958 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 14928 
    [ 2.500,  3.750) = 1088 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.401 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     11.027 ms/op
     p(99.9900) =     11.497 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.154 ms/op
Iteration   1: 3.623 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   0.607 ms/op
                 listUser·p0.50:   3.170 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   22.282 ms/op
                 listUser·p0.999:  30.321 ms/op
                 listUser·p0.9999: 39.453 ms/op
                 listUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8812
  mean =      3.623 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 390 
    [ 2.500,  5.000) = 8109 
    [ 5.000,  7.500) = 153 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =     22.282 ms/op
     p(99.9000) =     30.321 ms/op
     p(99.9900) =     39.453 ms/op
     p(99.9990) =     39.453 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.810          ops/ms
ClientSimple.existUser                       thrpt         12.531          ops/ms
ClientSimple.getUser                         thrpt         13.633          ops/ms
ClientSimple.listUser                        thrpt          8.554          ops/ms
ClientSimple.createUser                       avgt          2.111           ms/op
ClientSimple.existUser                        avgt          1.807           ms/op
ClientSimple.getUser                          avgt          2.136           ms/op
ClientSimple.listUser                         avgt          3.585           ms/op
ClientSimple.createUser                     sample  14961   2.140 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.608           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.829           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.059           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.372           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.869           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.296           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.507           ms/op
ClientSimple.existUser                      sample  16853   1.899 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.630           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.636           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.278           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.884           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.895           ms/op
ClientSimple.getUser                        sample  16318   1.958 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.864           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.401           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.346           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.027           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.497           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.518           ms/op
ClientSimple.listUser                       sample   8812   3.623 ± 0.090   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.607           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.170           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample         22.282           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.321           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         39.453           ms/op
ClientSimple.listUser:listUser·p1.00        sample         39.453           ms/op

Benchmark result is saved to 1714630308262.json
