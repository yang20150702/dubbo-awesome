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
# Warmup Iteration   1: 2.074 ops/ms
Iteration   1: 7.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.323 ops/ms


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
# Warmup Iteration   1: 7.645 ops/ms
Iteration   1: 12.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.337 ops/ms


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
# Warmup Iteration   1: 6.259 ops/ms
Iteration   1: 14.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.779 ops/ms


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
# Warmup Iteration   1: 4.969 ops/ms
Iteration   1: 7.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.274 ops/ms


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.077 ms/op
Iteration   1: 2.305 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.305 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.045 ms/op
Iteration   1: 2.080 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.055 ms/op
Iteration   1: 2.016 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.016 ms/op


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.086 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.067 ms/op


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
# Warmup Iteration   1: 3.559 ±(99.9%) 0.102 ms/op
Iteration   1: 2.376 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   2.265 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  30.867 ms/op
                 createUser·p0.9999: 33.266 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13486
  mean =      2.376 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9586 
    [ 2.500,  5.000) = 3756 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =     30.867 ms/op
     p(99.9900) =     33.266 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 2.867 ±(99.9%) 0.060 ms/op
Iteration   1: 1.753 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.087 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   3.068 ms/op
                 existUser·p0.999:  5.771 ms/op
                 existUser·p0.9999: 6.423 ms/op
                 existUser·p1.00:   6.504 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18241
  mean =      1.753 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 19 
    [1.000, 1.500) = 1613 
    [1.500, 2.000) = 14333 
    [2.000, 2.500) = 1818 
    [2.500, 3.000) = 259 
    [3.000, 3.500) = 69 
    [3.500, 4.000) = 25 
    [4.000, 4.500) = 7 
    [4.500, 5.000) = 32 
    [5.000, 5.500) = 9 
    [5.500, 6.000) = 43 
    [6.000, 6.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.087 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      3.068 ms/op
     p(99.9000) =      5.771 ms/op
     p(99.9900) =      6.423 ms/op
     p(99.9990) =      6.504 ms/op
     p(99.9999) =      6.504 ms/op
    p(100.0000) =      6.504 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.097 ms/op
Iteration   1: 2.015 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   1.860 ms/op
                 getUser·p0.90:   2.650 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   4.642 ms/op
                 getUser·p0.999:  14.657 ms/op
                 getUser·p0.9999: 17.342 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15877
  mean =      2.015 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 354 
    [ 1.250,  2.500) = 13090 
    [ 2.500,  3.750) = 2155 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      4.642 ms/op
     p(99.9000) =     14.657 ms/op
     p(99.9900) =     17.342 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.133 ms/op
Iteration   1: 3.587 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.444 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.515 ms/op
                 listUser·p0.999:  16.221 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8934
  mean =      3.587 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 320 
    [ 2.500,  3.750) = 5103 
    [ 3.750,  5.000) = 3277 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.444 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.515 ms/op
     p(99.9000) =     16.221 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.323          ops/ms
ClientSimple.existUser                       thrpt         12.337          ops/ms
ClientSimple.getUser                         thrpt         14.779          ops/ms
ClientSimple.listUser                        thrpt          7.274          ops/ms
ClientSimple.createUser                       avgt          2.305           ms/op
ClientSimple.existUser                        avgt          2.080           ms/op
ClientSimple.getUser                          avgt          2.016           ms/op
ClientSimple.listUser                         avgt          3.067           ms/op
ClientSimple.createUser                     sample  13486   2.376 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.483           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.265           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.063           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.867           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.266           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.358           ms/op
ClientSimple.existUser                      sample  18241   1.753 ± 0.009   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.787           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.087           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.068           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.771           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.423           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.504           ms/op
ClientSimple.getUser                        sample  15877   2.015 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.676           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.860           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.642           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.657           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.342           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.400           ms/op
ClientSimple.listUser                       sample   8934   3.587 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.618           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.444           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.515           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.221           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.924           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.924           ms/op

Benchmark result is saved to 1717135971967.json
