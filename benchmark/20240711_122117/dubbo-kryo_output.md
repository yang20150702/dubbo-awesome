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
# Warmup Iteration   1: 1.656 ops/ms
Iteration   1: 6.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.458 ops/ms


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
# Warmup Iteration   1: 6.477 ops/ms
Iteration   1: 12.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.158 ops/ms


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
# Warmup Iteration   1: 6.774 ops/ms
Iteration   1: 14.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.099 ops/ms


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
# Warmup Iteration   1: 5.261 ops/ms
Iteration   1: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.949 ops/ms


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.094 ms/op
Iteration   1: 2.149 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.149 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.045 ms/op
Iteration   1: 1.853 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.059 ms/op
Iteration   1: 2.208 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.208 ms/op


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.083 ms/op
Iteration   1: 3.781 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.781 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.128 ms/op
Iteration   1: 2.254 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.337 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   8.051 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 19.207 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14216
  mean =      2.254 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 361 
    [ 1.250,  2.500) = 11455 
    [ 2.500,  3.750) = 1884 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      8.051 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     19.207 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.103 ms/op
Iteration   1: 1.867 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  14.300 ms/op
                 existUser·p0.9999: 14.685 ms/op
                 existUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17112
  mean =      1.867 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 15866 
    [ 2.500,  3.750) = 983 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =     14.300 ms/op
     p(99.9900) =     14.685 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.082 ms/op
Iteration   1: 2.020 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   4.609 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 11.833 ms/op
                 getUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15818
  mean =      2.020 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 13814 
    [ 2.500,  3.750) = 1691 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      4.609 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     11.833 ms/op
     p(99.9990) =     11.862 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


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
# Warmup Iteration   1: 4.733 ±(99.9%) 0.151 ms/op
Iteration   1: 3.571 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.606 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.019 ms/op
                 listUser·p0.999:  14.730 ms/op
                 listUser·p0.9999: 15.008 ms/op
                 listUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8957
  mean =      3.571 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 800 
    [ 2.500,  3.750) = 5029 
    [ 3.750,  5.000) = 2765 
    [ 5.000,  6.250) = 228 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.019 ms/op
     p(99.9000) =     14.730 ms/op
     p(99.9900) =     15.008 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.458          ops/ms
ClientSimple.existUser                       thrpt         12.158          ops/ms
ClientSimple.getUser                         thrpt         14.099          ops/ms
ClientSimple.listUser                        thrpt          7.949          ops/ms
ClientSimple.createUser                       avgt          2.149           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.208           ms/op
ClientSimple.listUser                         avgt          3.781           ms/op
ClientSimple.createUser                     sample  14216   2.254 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.337           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.051           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.579           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.207           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.235           ms/op
ClientSimple.existUser                      sample  17112   1.867 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.486           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.685           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.696           ms/op
ClientSimple.getUser                        sample  15818   2.020 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.870           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.609           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.698           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.833           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.862           ms/op
ClientSimple.listUser                       sample   8957   3.571 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.606           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.019           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.730           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.008           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.008           ms/op

Benchmark result is saved to 1720700224195.json
