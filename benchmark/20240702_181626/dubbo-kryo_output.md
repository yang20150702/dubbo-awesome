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
# Warmup Iteration   1: 0.797 ops/ms
Iteration   1: 6.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.060 ops/ms


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
# Warmup Iteration   1: 6.694 ops/ms
Iteration   1: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.096 ops/ms


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
# Warmup Iteration   1: 5.641 ops/ms
Iteration   1: 13.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.787 ops/ms


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
# Warmup Iteration   1: 5.502 ops/ms
Iteration   1: 8.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.635 ops/ms


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.074 ms/op
Iteration   1: 2.147 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.147 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.050 ms/op
Iteration   1: 1.905 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.050 ms/op
Iteration   1: 1.910 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.910 ms/op


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.123 ms/op
Iteration   1: 3.648 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.648 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.074 ms/op
Iteration   1: 2.239 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.675 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  28.261 ms/op
                 createUser·p0.9999: 30.191 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14263
  mean =      2.239 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11934 
    [ 2.500,  5.000) = 2154 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     28.261 ms/op
     p(99.9900) =     30.191 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.082 ms/op
Iteration   1: 1.963 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.346 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 10.929 ms/op
                 existUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16169
  mean =      1.963 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 466 
    [ 1.250,  2.500) = 14311 
    [ 2.500,  3.750) = 1267 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.469 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     10.929 ms/op
     p(99.9990) =     11.010 ms/op
     p(99.9999) =     11.010 ms/op
    p(100.0000) =     11.010 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.268 ±(99.9%) 0.085 ms/op
Iteration   1: 1.953 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   1.749 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.470 ms/op
                 getUser·p0.99:   4.037 ms/op
                 getUser·p0.999:  39.453 ms/op
                 getUser·p0.9999: 39.738 ms/op
                 getUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16612
  mean =      1.953 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15879 
    [ 2.500,  5.000) = 633 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.037 ms/op
     p(99.9000) =     39.453 ms/op
     p(99.9900) =     39.738 ms/op
     p(99.9990) =     39.911 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.129 ms/op
Iteration   1: 3.399 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.577 ms/op
                 listUser·p0.99:   5.992 ms/op
                 listUser·p0.999:  8.110 ms/op
                 listUser·p0.9999: 9.634 ms/op
                 listUser·p1.00:   9.634 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9424
  mean =      3.399 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 15 
    [ 1.500,  2.000) = 48 
    [ 2.000,  2.500) = 646 
    [ 2.500,  3.000) = 2826 
    [ 3.000,  3.500) = 1771 
    [ 3.500,  4.000) = 2350 
    [ 4.000,  4.500) = 1238 
    [ 4.500,  5.000) = 233 
    [ 5.000,  5.500) = 164 
    [ 5.500,  6.000) = 41 
    [ 6.000,  6.500) = 47 
    [ 6.500,  7.000) = 2 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 31 
    [ 8.000,  8.500) = 7 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.577 ms/op
     p(99.0000) =      5.992 ms/op
     p(99.9000) =      8.110 ms/op
     p(99.9900) =      9.634 ms/op
     p(99.9990) =      9.634 ms/op
     p(99.9999) =      9.634 ms/op
    p(100.0000) =      9.634 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.060          ops/ms
ClientSimple.existUser                       thrpt         13.096          ops/ms
ClientSimple.getUser                         thrpt         13.787          ops/ms
ClientSimple.listUser                        thrpt          8.635          ops/ms
ClientSimple.createUser                       avgt          2.147           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          1.910           ms/op
ClientSimple.listUser                         avgt          3.648           ms/op
ClientSimple.createUser                     sample  14263   2.239 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.843           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.513           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.261           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.191           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.736           ms/op
ClientSimple.existUser                      sample  16169   1.963 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.346           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.886           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.469           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.764           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.929           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.010           ms/op
ClientSimple.getUser                        sample  16612   1.953 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.571           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.749           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.037           ms/op
ClientSimple.getUser:getUser·p0.999         sample         39.453           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         39.738           ms/op
ClientSimple.getUser:getUser·p1.00          sample         39.911           ms/op
ClientSimple.listUser                       sample   9424   3.399 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.577           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.992           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.110           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.634           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.634           ms/op

Benchmark result is saved to 1719943936411.json
