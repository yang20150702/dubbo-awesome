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
# Warmup Iteration   1: 1.735 ops/ms
Iteration   1: 7.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.058 ops/ms


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
# Warmup Iteration   1: 4.864 ops/ms
Iteration   1: 11.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.787 ops/ms


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
# Warmup Iteration   1: 5.345 ops/ms
Iteration   1: 13.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.995 ops/ms


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
# Warmup Iteration   1: 5.399 ops/ms
Iteration   1: 8.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.975 ops/ms


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.081 ms/op
Iteration   1: 2.106 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.106 ms/op


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
# Warmup Iteration   1: 2.969 ±(99.9%) 0.047 ms/op
Iteration   1: 2.025 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.025 ms/op


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.051 ms/op
Iteration   1: 1.956 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.956 ms/op


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.096 ms/op
Iteration   1: 3.188 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.188 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.079 ms/op
Iteration   1: 2.380 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   2.257 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.984 ms/op
                 createUser·p0.999:  32.739 ms/op
                 createUser·p0.9999: 37.159 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13439
  mean =      2.380 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8570 
    [ 2.500,  5.000) = 4770 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.257 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.984 ms/op
     p(99.9000) =     32.739 ms/op
     p(99.9900) =     37.159 ms/op
     p(99.9990) =     37.159 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.072 ms/op
Iteration   1: 1.734 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  17.352 ms/op
                 existUser·p0.9999: 17.650 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18445
  mean =      1.734 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1462 
    [ 1.250,  2.500) = 16370 
    [ 2.500,  3.750) = 447 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.428 ms/op
     p(99.9000) =     17.352 ms/op
     p(99.9900) =     17.650 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.079 ms/op
Iteration   1: 2.489 ±(99.9%) 0.143 ms/op
                 getUser·p0.00:   0.412 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   6.147 ms/op
                 getUser·p0.999:  104.887 ms/op
                 getUser·p0.9999: 117.058 ms/op
                 getUser·p1.00:   119.276 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12967
  mean =      2.489 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 12913 
    [ 12.500,  25.000) = 12 
    [ 25.000,  37.500) = 7 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 6 
    [ 87.500, 100.000) = 5 
    [100.000, 112.500) = 17 
    [112.500, 125.000) = 1 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      6.147 ms/op
     p(99.9000) =    104.887 ms/op
     p(99.9900) =    117.058 ms/op
     p(99.9990) =    119.276 ms/op
     p(99.9999) =    119.276 ms/op
    p(100.0000) =    119.276 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.125 ms/op
Iteration   1: 3.565 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.663 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.422 ms/op
                 listUser·p0.999:  7.627 ms/op
                 listUser·p0.9999: 7.979 ms/op
                 listUser·p1.00:   7.979 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9033
  mean =      3.565 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 187 
    [2.000, 2.500) = 565 
    [2.500, 3.000) = 1550 
    [3.000, 3.500) = 2168 
    [3.500, 4.000) = 2275 
    [4.000, 4.500) = 1005 
    [4.500, 5.000) = 759 
    [5.000, 5.500) = 284 
    [5.500, 6.000) = 91 
    [6.000, 6.500) = 32 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.422 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =      7.979 ms/op
     p(99.9990) =      7.979 ms/op
     p(99.9999) =      7.979 ms/op
    p(100.0000) =      7.979 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.058          ops/ms
ClientSimple.existUser                       thrpt          11.787          ops/ms
ClientSimple.getUser                         thrpt          13.995          ops/ms
ClientSimple.listUser                        thrpt           8.975          ops/ms
ClientSimple.createUser                       avgt           2.106           ms/op
ClientSimple.existUser                        avgt           2.025           ms/op
ClientSimple.getUser                          avgt           1.956           ms/op
ClientSimple.listUser                         avgt           3.188           ms/op
ClientSimple.createUser                     sample  13439    2.380 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.485           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.257           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample           3.984           ms/op
ClientSimple.createUser:createUser·p0.999   sample          32.739           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          37.159           ms/op
ClientSimple.createUser:createUser·p1.00    sample          37.159           ms/op
ClientSimple.existUser                      sample  18445    1.734 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.613           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.428           ms/op
ClientSimple.existUser:existUser·p0.999     sample          17.352           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          17.650           ms/op
ClientSimple.existUser:existUser·p1.00      sample          18.121           ms/op
ClientSimple.getUser                        sample  12967    2.489 ± 0.143   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.412           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.154           ms/op
ClientSimple.getUser:getUser·p0.99          sample           6.147           ms/op
ClientSimple.getUser:getUser·p0.999         sample         104.887           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         117.058           ms/op
ClientSimple.getUser:getUser·p1.00          sample         119.276           ms/op
ClientSimple.listUser                       sample   9033    3.565 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.663           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.694           ms/op
ClientSimple.listUser:listUser·p0.95        sample           5.038           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.422           ms/op
ClientSimple.listUser:listUser·p0.999       sample           7.627           ms/op
ClientSimple.listUser:listUser·p0.9999      sample           7.979           ms/op
ClientSimple.listUser:listUser·p1.00        sample           7.979           ms/op

Benchmark result is saved to 1716185557037.json
