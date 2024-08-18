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
# Warmup Iteration   1: 1.878 ops/ms
Iteration   1: 7.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.026 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.124 ops/ms
Iteration   1: 16.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  16.004 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ops/ms
Iteration   1: 12.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.139 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.762 ops/ms
Iteration   1: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.430 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.069 ms/op
Iteration   1: 2.137 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.137 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.050 ms/op
Iteration   1: 1.853 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.065 ms/op
Iteration   1: 2.233 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.233 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.087 ms/op
Iteration   1: 3.307 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.307 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.098 ms/op
Iteration   1: 2.109 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.498 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   8.204 ms/op
                 createUser·p0.999:  14.598 ms/op
                 createUser·p0.9999: 16.164 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15154
  mean =      2.109 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 13999 
    [ 2.500,  3.750) = 758 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      8.204 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     16.164 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.068 ms/op
Iteration   1: 1.892 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 11.108 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16904
  mean =      1.892 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 16026 
    [ 2.500,  3.750) = 469 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 3.414 ±(99.9%) 0.093 ms/op
Iteration   1: 1.906 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   1.860 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.593 ms/op
                 getUser·p0.99:   3.516 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 13.580 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16768
  mean =      1.906 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1096 
    [ 1.250,  2.500) = 14460 
    [ 2.500,  3.750) = 1066 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.516 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     13.580 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.132 ms/op
Iteration   1: 3.138 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 14.811 ms/op
                 listUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10201
  mean =      3.138 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2101 
    [ 2.500,  3.750) = 6182 
    [ 3.750,  5.000) = 1796 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.026          ops/ms
ClientSimple.existUser                       thrpt         16.004          ops/ms
ClientSimple.getUser                         thrpt         12.139          ops/ms
ClientSimple.listUser                        thrpt          9.430          ops/ms
ClientSimple.createUser                       avgt          2.137           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.233           ms/op
ClientSimple.listUser                         avgt          3.307           ms/op
ClientSimple.createUser                     sample  15154   2.109 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.498           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.204           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.598           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.164           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.679           ms/op
ClientSimple.existUser                      sample  16904   1.892 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.660           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.514           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.994           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.108           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.911           ms/op
ClientSimple.getUser                        sample  16768   1.906 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.665           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.860           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.516           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.502           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.580           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.123           ms/op
ClientSimple.listUser                       sample  10201   3.138 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.019           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.002           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.530           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.664           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.811           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.811           ms/op

Benchmark result is saved to 1723961524161.json
