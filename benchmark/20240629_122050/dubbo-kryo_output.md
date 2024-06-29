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
# Warmup Iteration   1: 0.831 ops/ms
Iteration   1: 5.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.635 ops/ms


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
# Warmup Iteration   1: 5.729 ops/ms
Iteration   1: 14.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.339 ops/ms


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
# Warmup Iteration   1: 4.555 ops/ms
Iteration   1: 12.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.378 ops/ms


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
# Warmup Iteration   1: 4.229 ops/ms
Iteration   1: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.496 ops/ms


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.081 ms/op
Iteration   1: 2.125 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.125 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.054 ms/op
Iteration   1: 2.029 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.029 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.066 ms/op
Iteration   1: 1.900 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.900 ms/op


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
# Warmup Iteration   1: 5.300 ±(99.9%) 0.148 ms/op
Iteration   1: 3.710 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.710 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.155 ms/op
Iteration   1: 2.278 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.492 ms/op
                 createUser·p0.999:  20.643 ms/op
                 createUser·p0.9999: 21.279 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14029
  mean =      2.278 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11293 
    [ 2.500,  5.000) = 2575 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.492 ms/op
     p(99.9000) =     20.643 ms/op
     p(99.9900) =     21.279 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.075 ms/op
Iteration   1: 2.144 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   2.114 ms/op
                 existUser·p0.90:   2.626 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   4.384 ms/op
                 existUser·p0.999:  24.904 ms/op
                 existUser·p0.9999: 25.313 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14990
  mean =      2.144 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12431 
    [ 2.500,  5.000) = 2471 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      4.384 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     25.313 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.085 ms/op
Iteration   1: 2.056 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.388 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   4.313 ms/op
                 getUser·p0.999:  13.664 ms/op
                 getUser·p0.9999: 14.157 ms/op
                 getUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15614
  mean =      2.056 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 13759 
    [ 2.500,  3.750) = 1495 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.313 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     14.157 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.808 ±(99.9%) 0.147 ms/op
Iteration   1: 3.393 ±(99.9%) 0.079 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.489 ms/op
                 listUser·p0.999:  39.487 ms/op
                 listUser·p0.9999: 46.334 ms/op
                 listUser·p1.00:   46.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9479
  mean =      3.393 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9109 
    [ 5.000, 10.000) = 299 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.489 ms/op
     p(99.9000) =     39.487 ms/op
     p(99.9900) =     46.334 ms/op
     p(99.9990) =     46.334 ms/op
     p(99.9999) =     46.334 ms/op
    p(100.0000) =     46.334 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.635          ops/ms
ClientSimple.existUser                       thrpt         14.339          ops/ms
ClientSimple.getUser                         thrpt         12.378          ops/ms
ClientSimple.listUser                        thrpt          8.496          ops/ms
ClientSimple.createUser                       avgt          2.125           ms/op
ClientSimple.existUser                        avgt          2.029           ms/op
ClientSimple.getUser                          avgt          1.900           ms/op
ClientSimple.listUser                         avgt          3.710           ms/op
ClientSimple.createUser                     sample  14029   2.278 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.706           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.297           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.764           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.492           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.643           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.279           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  14990   2.144 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.446           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.384           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.904           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.313           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.395           ms/op
ClientSimple.getUser                        sample  15614   2.056 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.388           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.313           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.664           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.157           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.221           ms/op
ClientSimple.listUser                       sample   9479   3.393 ± 0.079   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.489           ms/op
ClientSimple.listUser:listUser·p0.999       sample         39.487           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         46.334           ms/op
ClientSimple.listUser:listUser·p1.00        sample         46.334           ms/op

Benchmark result is saved to 1719663382679.json
