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
# Warmup Iteration   1: 1.822 ops/ms
Iteration   1: 7.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.135 ops/ms


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
# Warmup Iteration   1: 5.504 ops/ms
Iteration   1: 11.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.016 ops/ms


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
# Warmup Iteration   1: 4.448 ops/ms
Iteration   1: 12.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.321 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.105 ops/ms
Iteration   1: 8.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.004 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.083 ms/op
Iteration   1: 2.131 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.131 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.063 ms/op
Iteration   1: 2.090 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.090 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.062 ms/op
Iteration   1: 2.438 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.438 ms/op


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.093 ms/op
Iteration   1: 3.291 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.291 ms/op


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.104 ms/op
Iteration   1: 2.341 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   5.850 ms/op
                 createUser·p0.999:  26.488 ms/op
                 createUser·p0.9999: 36.783 ms/op
                 createUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13646
  mean =      2.341 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10035 
    [ 2.500,  5.000) = 3368 
    [ 5.000,  7.500) = 113 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      5.850 ms/op
     p(99.9000) =     26.488 ms/op
     p(99.9900) =     36.783 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.106 ms/op
Iteration   1: 1.992 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  13.139 ms/op
                 existUser·p0.9999: 13.340 ms/op
                 existUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16040
  mean =      1.992 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 14702 
    [ 2.500,  3.750) = 1006 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     13.139 ms/op
     p(99.9900) =     13.340 ms/op
     p(99.9990) =     13.369 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.086 ms/op
Iteration   1: 2.008 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   5.471 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 17.918 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15915
  mean =      2.008 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 292 
    [ 1.250,  2.500) = 14492 
    [ 2.500,  3.750) = 838 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      5.471 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     17.918 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.153 ms/op
Iteration   1: 3.706 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.388 ms/op
                 listUser·p0.999:  27.882 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8621
  mean =      3.706 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 753 
    [ 2.500,  5.000) = 7502 
    [ 5.000,  7.500) = 296 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.388 ms/op
     p(99.9000) =     27.882 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.135          ops/ms
ClientSimple.existUser                       thrpt         11.016          ops/ms
ClientSimple.getUser                         thrpt         12.321          ops/ms
ClientSimple.listUser                        thrpt          8.004          ops/ms
ClientSimple.createUser                       avgt          2.131           ms/op
ClientSimple.existUser                        avgt          2.090           ms/op
ClientSimple.getUser                          avgt          2.438           ms/op
ClientSimple.listUser                         avgt          3.291           ms/op
ClientSimple.createUser                     sample  13646   2.341 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.612           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.310           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.850           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.488           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.783           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.831           ms/op
ClientSimple.existUser                      sample  16040   1.992 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.882           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.325           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.139           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.340           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.369           ms/op
ClientSimple.getUser                        sample  15915   2.008 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.593           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.471           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.433           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.918           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.957           ms/op
ClientSimple.listUser                       sample   8621   3.706 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.671           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.662           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.388           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.882           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.045           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.045           ms/op

Benchmark result is saved to 1715084109912.json
