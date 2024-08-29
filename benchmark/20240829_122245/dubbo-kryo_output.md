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
# Warmup Iteration   1: 1.914 ops/ms
Iteration   1: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.064 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.065 ops/ms
Iteration   1: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.641 ops/ms


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
# Warmup Iteration   1: 6.236 ops/ms
Iteration   1: 14.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.074 ops/ms


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
# Warmup Iteration   1: 5.550 ops/ms
Iteration   1: 8.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.632 ops/ms


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.074 ms/op
Iteration   1: 2.203 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.203 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.913 ±(99.9%) 0.042 ms/op
Iteration   1: 1.647 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.647 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.233 ±(99.9%) 0.057 ms/op
Iteration   1: 1.913 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.913 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ±(99.9%) 0.073 ms/op
Iteration   1: 3.364 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.364 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.040 ±(99.9%) 0.108 ms/op
Iteration   1: 2.014 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   1.802 ms/op
                 createUser·p0.90:   2.388 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 17.427 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15949
  mean =      2.014 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 14636 
    [ 2.500,  3.750) = 946 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     17.427 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 2.708 ±(99.9%) 0.067 ms/op
Iteration   1: 2.091 ±(99.9%) 0.071 ms/op
                 existUser·p0.00:   0.310 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   4.779 ms/op
                 existUser·p0.999:  59.093 ms/op
                 existUser·p0.9999: 59.599 ms/op
                 existUser·p1.00:   59.703 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15314
  mean =      2.091 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15166 
    [ 5.000, 10.000) = 43 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      4.779 ms/op
     p(99.9000) =     59.093 ms/op
     p(99.9900) =     59.599 ms/op
     p(99.9990) =     59.703 ms/op
     p(99.9999) =     59.703 ms/op
    p(100.0000) =     59.703 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.074 ms/op
Iteration   1: 2.145 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  11.792 ms/op
                 getUser·p0.9999: 12.550 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14929
  mean =      2.145 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 315 
    [ 1.250,  2.500) = 12182 
    [ 2.500,  3.750) = 2235 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     11.792 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.163 ms/op
Iteration   1: 3.371 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  7.966 ms/op
                 listUser·p0.9999: 8.700 ms/op
                 listUser·p1.00:   8.700 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9516
  mean =      3.371 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 102 
    [2.000, 2.500) = 582 
    [2.500, 3.000) = 2823 
    [3.000, 3.500) = 2181 
    [3.500, 4.000) = 2289 
    [4.000, 4.500) = 938 
    [4.500, 5.000) = 311 
    [5.000, 5.500) = 87 
    [5.500, 6.000) = 115 
    [6.000, 6.500) = 37 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 25 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =      7.966 ms/op
     p(99.9900) =      8.700 ms/op
     p(99.9990) =      8.700 ms/op
     p(99.9999) =      8.700 ms/op
    p(100.0000) =      8.700 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.064          ops/ms
ClientSimple.existUser                       thrpt         12.641          ops/ms
ClientSimple.getUser                         thrpt         14.074          ops/ms
ClientSimple.listUser                        thrpt          8.632          ops/ms
ClientSimple.createUser                       avgt          2.203           ms/op
ClientSimple.existUser                        avgt          1.647           ms/op
ClientSimple.getUser                          avgt          1.913           ms/op
ClientSimple.listUser                         avgt          3.364           ms/op
ClientSimple.createUser                     sample  15949   2.014 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.851           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.802           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.388           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.513           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.941           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.427           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.564           ms/op
ClientSimple.existUser                      sample  15314   2.091 ± 0.071   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.310           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.779           ms/op
ClientSimple.existUser:existUser·p0.999     sample         59.093           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         59.599           ms/op
ClientSimple.existUser:existUser·p1.00      sample         59.703           ms/op
ClientSimple.getUser                        sample  14929   2.145 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.965           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.792           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.550           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.567           ms/op
ClientSimple.listUser                       sample   9516   3.371 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.112           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.248           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.874           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.966           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.700           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.700           ms/op

Benchmark result is saved to 1724933909821.json
