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
# Warmup Iteration   1: 1.684 ops/ms
Iteration   1: 7.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.210 ops/ms


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
# Warmup Iteration   1: 7.282 ops/ms
Iteration   1: 12.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.548 ops/ms


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
# Warmup Iteration   1: 5.194 ops/ms
Iteration   1: 12.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.360 ops/ms


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
# Warmup Iteration   1: 5.279 ops/ms
Iteration   1: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.442 ops/ms


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.079 ms/op
Iteration   1: 1.974 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.086 ms/op
Iteration   1: 1.945 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.945 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.064 ms/op
Iteration   1: 1.937 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.937 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.093 ms/op
Iteration   1: 3.423 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.423 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.085 ms/op
Iteration   1: 2.036 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   1.849 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.838 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  18.317 ms/op
                 createUser·p0.9999: 19.570 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15743
  mean =      2.036 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14192 
    [ 2.500,  5.000) = 1347 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.838 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     19.570 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.093 ms/op
Iteration   1: 1.774 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.265 ms/op
                 existUser·p0.99:   2.988 ms/op
                 existUser·p0.999:  21.789 ms/op
                 existUser·p0.9999: 23.239 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18057
  mean =      1.774 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17676 
    [ 2.500,  5.000) = 336 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.265 ms/op
     p(99.0000) =      2.988 ms/op
     p(99.9000) =     21.789 ms/op
     p(99.9900) =     23.239 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.079 ms/op
Iteration   1: 1.975 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  16.052 ms/op
                 getUser·p0.9999: 16.122 ms/op
                 getUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16252
  mean =      1.975 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 14005 
    [ 2.500,  3.750) = 1912 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =     16.052 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     16.122 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.144 ms/op
Iteration   1: 3.975 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  12.221 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8082
  mean =      3.975 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 483 
    [ 2.500,  3.750) = 2518 
    [ 3.750,  5.000) = 4360 
    [ 5.000,  6.250) = 593 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     12.221 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.210          ops/ms
ClientSimple.existUser                       thrpt         12.548          ops/ms
ClientSimple.getUser                         thrpt         12.360          ops/ms
ClientSimple.listUser                        thrpt          8.442          ops/ms
ClientSimple.createUser                       avgt          1.974           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          1.937           ms/op
ClientSimple.listUser                         avgt          3.423           ms/op
ClientSimple.createUser                     sample  15743   2.036 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.935           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.849           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.838           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.431           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.317           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.570           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.021           ms/op
ClientSimple.existUser                      sample  18057   1.774 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.696           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.663           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.988           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.789           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.239           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.265           ms/op
ClientSimple.getUser                        sample  16252   1.975 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.112           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.052           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.122           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.122           ms/op
ClientSimple.listUser                       sample   8082   3.975 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.953           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.300           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.471           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.221           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.680           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.680           ms/op

Benchmark result is saved to 1716012680268.json
