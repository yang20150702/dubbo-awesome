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
# Warmup Iteration   1: 0.894 ops/ms
Iteration   1: 6.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.259 ops/ms


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
# Warmup Iteration   1: 6.078 ops/ms
Iteration   1: 11.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.664 ops/ms


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
# Warmup Iteration   1: 5.472 ops/ms
Iteration   1: 14.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.094 ops/ms


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
# Warmup Iteration   1: 5.133 ops/ms
Iteration   1: 8.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.805 ops/ms


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.084 ms/op
Iteration   1: 2.321 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.321 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.052 ms/op
Iteration   1: 2.047 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.047 ms/op


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
# Warmup Iteration   1: 3.158 ±(99.9%) 0.063 ms/op
Iteration   1: 2.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.031 ms/op


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
# Warmup Iteration   1: 5.693 ±(99.9%) 0.118 ms/op
Iteration   1: 3.268 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.268 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.090 ms/op
Iteration   1: 2.309 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.863 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  28.376 ms/op
                 createUser·p0.9999: 29.570 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14021
  mean =      2.309 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10244 
    [ 2.500,  5.000) = 3607 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     28.376 ms/op
     p(99.9900) =     29.570 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 2.914 ±(99.9%) 0.063 ms/op
Iteration   1: 1.819 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.433 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.602 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  26.690 ms/op
                 existUser·p0.9999: 28.107 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18094
  mean =      1.819 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16918 
    [ 2.500,  5.000) = 1047 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.602 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =     26.690 ms/op
     p(99.9900) =     28.107 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.072 ms/op
Iteration   1: 2.005 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  16.876 ms/op
                 getUser·p0.9999: 17.347 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15981
  mean =      2.005 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 223 
    [ 1.250,  2.500) = 14336 
    [ 2.500,  3.750) = 1066 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     17.347 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.124 ms/op
Iteration   1: 3.184 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.805 ms/op
                 listUser·p0.999:  10.731 ms/op
                 listUser·p0.9999: 11.140 ms/op
                 listUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10033
  mean =      3.184 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 1775 
    [ 2.500,  3.750) = 6324 
    [ 3.750,  5.000) = 1695 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.805 ms/op
     p(99.9000) =     10.731 ms/op
     p(99.9900) =     11.140 ms/op
     p(99.9990) =     11.141 ms/op
     p(99.9999) =     11.141 ms/op
    p(100.0000) =     11.141 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.259          ops/ms
ClientSimple.existUser                       thrpt         11.664          ops/ms
ClientSimple.getUser                         thrpt         14.094          ops/ms
ClientSimple.listUser                        thrpt          8.805          ops/ms
ClientSimple.createUser                       avgt          2.321           ms/op
ClientSimple.existUser                        avgt          2.047           ms/op
ClientSimple.getUser                          avgt          2.031           ms/op
ClientSimple.listUser                         avgt          3.268           ms/op
ClientSimple.createUser                     sample  14021   2.309 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.982           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.603           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.376           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.570           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.622           ms/op
ClientSimple.existUser                      sample  18094   1.819 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.433           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.602           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.690           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.107           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.213           ms/op
ClientSimple.getUser                        sample  15981   2.005 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.585           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.160           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.876           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.347           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.367           ms/op
ClientSimple.listUser                       sample  10033   3.184 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.805           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.731           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.140           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.141           ms/op

Benchmark result is saved to 1719749757518.json
