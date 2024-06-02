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
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.693 ops/ms


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
# Warmup Iteration   1: 6.457 ops/ms
Iteration   1: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.780 ops/ms


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
# Warmup Iteration   1: 5.920 ops/ms
Iteration   1: 12.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.515 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.742 ops/ms
Iteration   1: 8.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.109 ops/ms


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.070 ms/op
Iteration   1: 1.897 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.897 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.051 ms/op
Iteration   1: 1.838 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.838 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.056 ms/op
Iteration   1: 1.758 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.758 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.074 ms/op
Iteration   1: 2.884 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.884 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.079 ms/op
Iteration   1: 2.152 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.410 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.769 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  24.155 ms/op
                 createUser·p0.9999: 24.958 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14839
  mean =      2.152 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12717 
    [ 2.500,  5.000) = 1893 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     24.155 ms/op
     p(99.9900) =     24.958 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.073 ms/op
Iteration   1: 1.701 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   1.626 ms/op
                 existUser·p0.90:   1.909 ms/op
                 existUser·p0.95:   2.097 ms/op
                 existUser·p0.99:   2.642 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 21.172 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18800
  mean =      1.701 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18560 
    [ 2.500,  5.000) = 202 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      1.626 ms/op
     p(90.0000) =      1.909 ms/op
     p(95.0000) =      2.097 ms/op
     p(99.0000) =      2.642 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     21.172 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.175 ±(99.9%) 0.073 ms/op
Iteration   1: 2.157 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   2.009 ms/op
                 getUser·p0.90:   2.879 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 24.808 ms/op
                 getUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14809
  mean =      2.157 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11715 
    [ 2.500,  5.000) = 3025 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     24.808 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.125 ms/op
Iteration   1: 3.128 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.234 ms/op
                 listUser·p0.99:   5.225 ms/op
                 listUser·p0.999:  11.169 ms/op
                 listUser·p0.9999: 12.533 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10221
  mean =      3.128 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1668 
    [ 2.500,  3.750) = 6738 
    [ 3.750,  5.000) = 1649 
    [ 5.000,  6.250) = 131 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.234 ms/op
     p(99.0000) =      5.225 ms/op
     p(99.9000) =     11.169 ms/op
     p(99.9900) =     12.533 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.693          ops/ms
ClientSimple.existUser                       thrpt         12.780          ops/ms
ClientSimple.getUser                         thrpt         12.515          ops/ms
ClientSimple.listUser                        thrpt          8.109          ops/ms
ClientSimple.createUser                       avgt          1.897           ms/op
ClientSimple.existUser                        avgt          1.838           ms/op
ClientSimple.getUser                          avgt          1.758           ms/op
ClientSimple.listUser                         avgt          2.884           ms/op
ClientSimple.createUser                     sample  14839   2.152 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.410           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.224           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.155           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.958           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.100           ms/op
ClientSimple.existUser                      sample  18800   1.701 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.806           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.626           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.172           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.201           ms/op
ClientSimple.getUser                        sample  14809   2.157 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.534           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.009           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.584           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.183           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.808           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.871           ms/op
ClientSimple.listUser                       sample  10221   3.128 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.893           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.932           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.234           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.225           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.169           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.533           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.534           ms/op

Benchmark result is saved to 1717351908084.json
