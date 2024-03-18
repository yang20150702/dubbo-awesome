# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.069 ops/ms
Iteration   1: 7.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.396 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.100 ops/ms
Iteration   1: 14.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.067 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.296 ops/ms
Iteration   1: 15.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.146 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.816 ops/ms
Iteration   1: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.573 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.074 ms/op
Iteration   1: 2.287 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.071 ±(99.9%) 0.046 ms/op
Iteration   1: 1.686 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.168 ±(99.9%) 0.053 ms/op
Iteration   1: 2.072 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.328 ±(99.9%) 0.112 ms/op
Iteration   1: 3.063 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.099 ms/op
Iteration   1: 2.087 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   6.992 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 19.447 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15251
  mean =      2.087 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 13090 
    [ 2.500,  3.750) = 1766 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      6.992 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     19.447 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.155 ±(99.9%) 0.076 ms/op
Iteration   1: 1.804 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  17.990 ms/op
                 existUser·p0.9999: 19.181 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17709
  mean =      1.804 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 256 
    [ 1.250,  2.500) = 16686 
    [ 2.500,  3.750) = 589 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     19.181 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.418 ±(99.9%) 0.092 ms/op
Iteration   1: 1.910 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   1.726 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   3.501 ms/op
                 getUser·p0.999:  16.145 ms/op
                 getUser·p0.9999: 16.598 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16733
  mean =      1.910 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 306 
    [ 1.250,  2.500) = 14737 
    [ 2.500,  3.750) = 1543 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.501 ms/op
     p(99.9000) =     16.145 ms/op
     p(99.9900) =     16.598 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.110 ms/op
Iteration   1: 3.445 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.453 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  6.980 ms/op
                 listUser·p0.9999: 7.217 ms/op
                 listUser·p1.00:   7.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9326
  mean =      3.445 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 132 
    [2.000, 2.500) = 858 
    [2.500, 3.000) = 2388 
    [3.000, 3.500) = 1455 
    [3.500, 4.000) = 2156 
    [4.000, 4.500) = 1586 
    [4.500, 5.000) = 357 
    [5.000, 5.500) = 129 
    [5.500, 6.000) = 150 
    [6.000, 6.500) = 48 
    [6.500, 7.000) = 40 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =      7.217 ms/op
     p(99.9990) =      7.217 ms/op
     p(99.9999) =      7.217 ms/op
    p(100.0000) =      7.217 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.396          ops/ms
ClientSimple.existUser                       thrpt         14.067          ops/ms
ClientSimple.getUser                         thrpt         15.146          ops/ms
ClientSimple.listUser                        thrpt          8.573          ops/ms
ClientSimple.createUser                       avgt          2.287           ms/op
ClientSimple.existUser                        avgt          1.686           ms/op
ClientSimple.getUser                          avgt          2.072           ms/op
ClientSimple.listUser                         avgt          3.063           ms/op
ClientSimple.createUser                     sample  15251   2.087 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.821           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.992           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.302           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.447           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.464           ms/op
ClientSimple.existUser                      sample  17709   1.804 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.673           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.801           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.990           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.181           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.661           ms/op
ClientSimple.getUser                        sample  16733   1.910 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.754           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.726           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.501           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.145           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.598           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.007           ms/op
ClientSimple.listUser                       sample   9326   3.445 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.878           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.453           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.980           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.217           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.217           ms/op

Benchmark result is saved to 1710785439829.json
