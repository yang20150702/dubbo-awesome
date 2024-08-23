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
# Warmup Iteration   1: 1.055 ops/ms
Iteration   1: 5.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.182 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.686 ops/ms
Iteration   1: 12.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.017 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.839 ops/ms
Iteration   1: 11.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.933 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ops/ms
Iteration   1: 7.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.274 ops/ms


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
# Warmup Iteration   1: 4.870 ±(99.9%) 0.127 ms/op
Iteration   1: 2.454 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.454 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.265 ±(99.9%) 0.063 ms/op
Iteration   1: 2.148 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.148 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ±(99.9%) 0.076 ms/op
Iteration   1: 2.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.098 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.109 ms/op
Iteration   1: 3.876 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.876 ms/op


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.113 ms/op
Iteration   1: 2.458 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   3.471 ms/op
                 createUser·p0.95:   3.874 ms/op
                 createUser·p0.99:   6.432 ms/op
                 createUser·p0.999:  18.154 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12985
  mean =      2.458 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 8157 
    [ 2.500,  3.750) = 3888 
    [ 3.750,  5.000) = 407 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      3.471 ms/op
     p(95.0000) =      3.874 ms/op
     p(99.0000) =      6.432 ms/op
     p(99.9000) =     18.154 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.102 ±(99.9%) 0.074 ms/op
Iteration   1: 1.906 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.387 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   4.898 ms/op
                 existUser·p0.999:  14.913 ms/op
                 existUser·p0.9999: 18.230 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16810
  mean =      1.906 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 313 
    [ 1.250,  2.500) = 15412 
    [ 2.500,  3.750) = 782 
    [ 3.750,  5.000) = 169 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      4.898 ms/op
     p(99.9000) =     14.913 ms/op
     p(99.9900) =     18.230 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.113 ms/op
Iteration   1: 1.899 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   1.827 ms/op
                 getUser·p0.90:   2.302 ms/op
                 getUser·p0.95:   2.523 ms/op
                 getUser·p0.99:   4.274 ms/op
                 getUser·p0.999:  14.483 ms/op
                 getUser·p0.9999: 15.027 ms/op
                 getUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17022
  mean =      1.899 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 371 
    [ 1.250,  2.500) = 15747 
    [ 2.500,  3.750) = 629 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      4.274 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     15.027 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 5.266 ±(99.9%) 0.145 ms/op
Iteration   1: 3.503 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.762 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  25.845 ms/op
                 listUser·p0.9999: 26.444 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9134
  mean =      3.503 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 807 
    [ 2.500,  5.000) = 8030 
    [ 5.000,  7.500) = 222 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.762 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     25.845 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.182          ops/ms
ClientSimple.existUser                       thrpt         12.017          ops/ms
ClientSimple.getUser                         thrpt         11.933          ops/ms
ClientSimple.listUser                        thrpt          7.274          ops/ms
ClientSimple.createUser                       avgt          2.454           ms/op
ClientSimple.existUser                        avgt          2.148           ms/op
ClientSimple.getUser                          avgt          2.098           ms/op
ClientSimple.listUser                         avgt          3.876           ms/op
ClientSimple.createUser                     sample  12985   2.458 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.602           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.471           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.874           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.432           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.154           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.005           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.005           ms/op
ClientSimple.existUser                      sample  16810   1.906 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.387           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.898           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.913           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.230           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.743           ms/op
ClientSimple.getUser                        sample  17022   1.899 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.558           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.827           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.302           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.274           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.483           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.027           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.188           ms/op
ClientSimple.listUser                       sample   9134   3.503 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.956           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.762           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.845           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.444           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.444           ms/op

Benchmark result is saved to 1724393616340.json
