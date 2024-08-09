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
# Warmup Iteration   1: 1.479 ops/ms
Iteration   1: 5.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.971 ops/ms


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
# Warmup Iteration   1: 5.936 ops/ms
Iteration   1: 11.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.085 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.989 ops/ms
Iteration   1: 9.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.358 ops/ms


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
# Warmup Iteration   1: 3.690 ops/ms
Iteration   1: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.163 ops/ms


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.069 ms/op
Iteration   1: 2.215 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.058 ms/op
Iteration   1: 1.788 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.788 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.066 ms/op
Iteration   1: 2.108 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.108 ms/op


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.102 ms/op
Iteration   1: 3.550 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.550 ms/op


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.131 ms/op
Iteration   1: 2.519 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   2.249 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   9.521 ms/op
                 createUser·p0.999:  30.877 ms/op
                 createUser·p0.9999: 33.412 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12708
  mean =      2.519 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8966 
    [ 2.500,  5.000) = 3420 
    [ 5.000,  7.500) = 153 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =      9.521 ms/op
     p(99.9000) =     30.877 ms/op
     p(99.9900) =     33.412 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.088 ms/op
Iteration   1: 2.403 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.372 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  13.758 ms/op
                 existUser·p0.9999: 14.527 ms/op
                 existUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13303
  mean =      2.403 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 8244 
    [ 2.500,  3.750) = 4873 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =     13.758 ms/op
     p(99.9900) =     14.527 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.104 ms/op
Iteration   1: 2.494 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   2.265 ms/op
                 getUser·p0.90:   3.269 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   6.714 ms/op
                 getUser·p0.999:  13.831 ms/op
                 getUser·p0.9999: 14.575 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12841
  mean =      2.494 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 8345 
    [ 2.500,  3.750) = 3737 
    [ 3.750,  5.000) = 432 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      6.714 ms/op
     p(99.9000) =     13.831 ms/op
     p(99.9900) =     14.575 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.137 ms/op
Iteration   1: 3.658 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.449 ms/op
                 listUser·p0.999:  16.159 ms/op
                 listUser·p0.9999: 16.630 ms/op
                 listUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8733
  mean =      3.658 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 892 
    [ 2.500,  3.750) = 4288 
    [ 3.750,  5.000) = 3194 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.449 ms/op
     p(99.9000) =     16.159 ms/op
     p(99.9900) =     16.630 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.971          ops/ms
ClientSimple.existUser                       thrpt         11.085          ops/ms
ClientSimple.getUser                         thrpt          9.358          ops/ms
ClientSimple.listUser                        thrpt          8.163          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          1.788           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.550           ms/op
ClientSimple.createUser                     sample  12708   2.519 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.812           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.391           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.521           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.877           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.412           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.456           ms/op
ClientSimple.existUser                      sample  13303   2.403 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.746           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.068           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.744           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.758           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.527           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.533           ms/op
ClientSimple.getUser                        sample  12841   2.494 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.848           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.269           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.772           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.714           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.831           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.575           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.696           ms/op
ClientSimple.listUser                       sample   8733   3.658 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.348           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.580           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.449           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.159           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.630           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.630           ms/op

Benchmark result is saved to 1723205865030.json
