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
# Warmup Iteration   1: 1.649 ops/ms
Iteration   1: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.793 ops/ms


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
# Warmup Iteration   1: 6.782 ops/ms
Iteration   1: 13.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.009 ops/ms


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
# Warmup Iteration   1: 7.421 ops/ms
Iteration   1: 14.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.282 ops/ms


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
# Warmup Iteration   1: 4.969 ops/ms
Iteration   1: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.364 ops/ms


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.080 ms/op
Iteration   1: 2.069 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.069 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.066 ms/op
Iteration   1: 2.052 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.052 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.054 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.473 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.076 ms/op
Iteration   1: 3.701 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.701 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.113 ms/op
Iteration   1: 2.259 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   2.005 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   6.091 ms/op
                 createUser·p0.999:  33.396 ms/op
                 createUser·p0.9999: 36.682 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14275
  mean =      2.259 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10928 
    [ 2.500,  5.000) = 3169 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      6.091 ms/op
     p(99.9000) =     33.396 ms/op
     p(99.9900) =     36.682 ms/op
     p(99.9990) =     36.766 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.104 ms/op
Iteration   1: 1.830 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 12.456 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17474
  mean =      1.830 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 850 
    [ 1.250,  2.500) = 15850 
    [ 2.500,  3.750) = 531 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.456 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.091 ms/op
Iteration   1: 1.906 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   1.753 ms/op
                 getUser·p0.90:   2.314 ms/op
                 getUser·p0.95:   2.564 ms/op
                 getUser·p0.99:   3.180 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 18.074 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16788
  mean =      1.906 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 303 
    [ 1.250,  2.500) = 15471 
    [ 2.500,  3.750) = 866 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.180 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     18.074 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.479 ±(99.9%) 0.114 ms/op
Iteration   1: 3.743 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  14.153 ms/op
                 listUser·p0.9999: 15.188 ms/op
                 listUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8548
  mean =      3.743 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 426 
    [ 2.500,  3.750) = 4164 
    [ 3.750,  5.000) = 3607 
    [ 5.000,  6.250) = 209 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     14.153 ms/op
     p(99.9900) =     15.188 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.793          ops/ms
ClientSimple.existUser                       thrpt         13.009          ops/ms
ClientSimple.getUser                         thrpt         14.282          ops/ms
ClientSimple.listUser                        thrpt          9.364          ops/ms
ClientSimple.createUser                       avgt          2.069           ms/op
ClientSimple.existUser                        avgt          2.052           ms/op
ClientSimple.getUser                          avgt          2.473           ms/op
ClientSimple.listUser                         avgt          3.701           ms/op
ClientSimple.createUser                     sample  14275   2.259 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.526           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.005           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.301           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.091           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.396           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.682           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.766           ms/op
ClientSimple.existUser                      sample  17474   1.830 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.740           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.731           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.686           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.042           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.456           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.616           ms/op
ClientSimple.getUser                        sample  16788   1.906 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.632           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.753           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.314           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.180           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.465           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.074           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.252           ms/op
ClientSimple.listUser                       sample   8548   3.743 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.711           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.454           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.153           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.188           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.188           ms/op

Benchmark result is saved to 1720721558817.json
