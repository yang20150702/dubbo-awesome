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
# Warmup Iteration   1: 1.675 ops/ms
Iteration   1: 6.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.838 ops/ms


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
# Warmup Iteration   1: 5.684 ops/ms
Iteration   1: 12.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.627 ops/ms


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
# Warmup Iteration   1: 5.603 ops/ms
Iteration   1: 13.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.128 ops/ms


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
# Warmup Iteration   1: 5.330 ops/ms
Iteration   1: 8.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.555 ops/ms


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.066 ms/op
Iteration   1: 2.126 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.126 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.053 ms/op
Iteration   1: 1.781 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.781 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.049 ms/op
Iteration   1: 2.211 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.211 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.079 ms/op
Iteration   1: 4.057 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.057 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.085 ms/op
Iteration   1: 2.357 ±(99.9%) 0.121 ms/op
                 createUser·p0.00:   0.376 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   14.525 ms/op
                 createUser·p0.999:  81.011 ms/op
                 createUser·p0.9999: 103.791 ms/op
                 createUser·p1.00:   107.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13561
  mean =      2.357 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13415 
    [ 12.500,  25.000) = 73 
    [ 25.000,  37.500) = 35 
    [ 37.500,  50.000) = 9 
    [ 50.000,  62.500) = 5 
    [ 62.500,  75.000) = 6 
    [ 75.000,  87.500) = 9 
    [ 87.500, 100.000) = 8 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =     14.525 ms/op
     p(99.9000) =     81.011 ms/op
     p(99.9900) =    103.791 ms/op
     p(99.9990) =    107.479 ms/op
     p(99.9999) =    107.479 ms/op
    p(100.0000) =    107.479 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.079 ms/op
Iteration   1: 1.930 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   4.486 ms/op
                 existUser·p0.999:  16.187 ms/op
                 existUser·p0.9999: 16.801 ms/op
                 existUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16576
  mean =      1.930 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 408 
    [ 1.250,  2.500) = 14440 
    [ 2.500,  3.750) = 1553 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      4.486 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     16.801 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.021 ±(99.9%) 0.067 ms/op
Iteration   1: 2.153 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.514 ms/op
                 getUser·p0.50:   2.071 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   3.488 ms/op
                 getUser·p0.999:  16.886 ms/op
                 getUser·p0.9999: 17.369 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14834
  mean =      2.153 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 11066 
    [ 2.500,  3.750) = 3555 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      3.488 ms/op
     p(99.9000) =     16.886 ms/op
     p(99.9900) =     17.369 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.134 ms/op
Iteration   1: 3.339 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.109 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.859 ms/op
                 listUser·p0.999:  7.134 ms/op
                 listUser·p0.9999: 7.725 ms/op
                 listUser·p1.00:   7.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9682
  mean =      3.339 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 17 
    [1.500, 2.000) = 61 
    [2.000, 2.500) = 847 
    [2.500, 3.000) = 3290 
    [3.000, 3.500) = 1831 
    [3.500, 4.000) = 1602 
    [4.000, 4.500) = 1355 
    [4.500, 5.000) = 399 
    [5.000, 5.500) = 138 
    [5.500, 6.000) = 57 
    [6.000, 6.500) = 48 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.859 ms/op
     p(99.9000) =      7.134 ms/op
     p(99.9900) =      7.725 ms/op
     p(99.9990) =      7.725 ms/op
     p(99.9999) =      7.725 ms/op
    p(100.0000) =      7.725 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.838          ops/ms
ClientSimple.existUser                       thrpt          12.627          ops/ms
ClientSimple.getUser                         thrpt          13.128          ops/ms
ClientSimple.listUser                        thrpt           8.555          ops/ms
ClientSimple.createUser                       avgt           2.126           ms/op
ClientSimple.existUser                        avgt           1.781           ms/op
ClientSimple.getUser                          avgt           2.211           ms/op
ClientSimple.listUser                         avgt           4.057           ms/op
ClientSimple.createUser                     sample  13561    2.357 ± 0.121   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.376           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample          14.525           ms/op
ClientSimple.createUser:createUser·p0.999   sample          81.011           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         103.791           ms/op
ClientSimple.createUser:createUser·p1.00    sample         107.479           ms/op
ClientSimple.existUser                      sample  16576    1.930 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.651           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.486           ms/op
ClientSimple.existUser:existUser·p0.999     sample          16.187           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          16.801           ms/op
ClientSimple.existUser:existUser·p1.00      sample          16.908           ms/op
ClientSimple.getUser                        sample  14834    2.153 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.514           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.071           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.488           ms/op
ClientSimple.getUser:getUser·p0.999         sample          16.886           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          17.369           ms/op
ClientSimple.getUser:getUser·p1.00          sample          17.433           ms/op
ClientSimple.listUser                       sample   9682    3.339 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.135           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.109           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.859           ms/op
ClientSimple.listUser:listUser·p0.999       sample           7.134           ms/op
ClientSimple.listUser:listUser·p0.9999      sample           7.725           ms/op
ClientSimple.listUser:listUser·p1.00        sample           7.725           ms/op

Benchmark result is saved to 1714241387077.json
