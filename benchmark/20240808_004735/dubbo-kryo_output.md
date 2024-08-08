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
# Warmup Iteration   1: 1.678 ops/ms
Iteration   1: 6.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.817 ops/ms


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
# Warmup Iteration   1: 6.458 ops/ms
Iteration   1: 12.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.692 ops/ms


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
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 12.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.911 ops/ms


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
# Warmup Iteration   1: 3.747 ops/ms
Iteration   1: 8.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.762 ops/ms


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.061 ms/op
Iteration   1: 2.125 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.125 ms/op


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
# Warmup Iteration   1: 3.188 ±(99.9%) 0.047 ms/op
Iteration   1: 1.870 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.870 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.064 ms/op
Iteration   1: 2.093 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.093 ms/op


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.084 ms/op
Iteration   1: 3.406 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.406 ms/op


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
# Warmup Iteration   1: 3.595 ±(99.9%) 0.086 ms/op
Iteration   1: 2.082 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   4.403 ms/op
                 createUser·p0.999:  12.452 ms/op
                 createUser·p0.9999: 13.664 ms/op
                 createUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15552
  mean =      2.082 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 13945 
    [ 2.500,  3.750) = 1198 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.403 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.077 ms/op
Iteration   1: 1.834 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   3.187 ms/op
                 existUser·p0.999:  11.085 ms/op
                 existUser·p0.9999: 11.494 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17446
  mean =      1.834 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 15795 
    [ 2.500,  3.750) = 1503 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =     11.085 ms/op
     p(99.9900) =     11.494 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.076 ms/op
Iteration   1: 2.036 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   1.888 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.765 ms/op
                 getUser·p0.99:   3.323 ms/op
                 getUser·p0.999:  14.467 ms/op
                 getUser·p0.9999: 15.088 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15753
  mean =      2.036 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 13424 
    [ 2.500,  3.750) = 2099 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      3.323 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     15.088 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.131 ms/op
Iteration   1: 3.574 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.671 ms/op
                 listUser·p0.99:   7.131 ms/op
                 listUser·p0.999:  29.034 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8956
  mean =      3.574 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 719 
    [ 2.500,  5.000) = 7894 
    [ 5.000,  7.500) = 271 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.671 ms/op
     p(99.0000) =      7.131 ms/op
     p(99.9000) =     29.034 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.817          ops/ms
ClientSimple.existUser                       thrpt         12.692          ops/ms
ClientSimple.getUser                         thrpt         12.911          ops/ms
ClientSimple.listUser                        thrpt          8.762          ops/ms
ClientSimple.createUser                       avgt          2.125           ms/op
ClientSimple.existUser                        avgt          1.870           ms/op
ClientSimple.getUser                          avgt          2.093           ms/op
ClientSimple.listUser                         avgt          3.406           ms/op
ClientSimple.createUser                     sample  15552   2.082 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.878           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.403           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.452           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.664           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.664           ms/op
ClientSimple.existUser                      sample  17446   1.834 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.499           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.667           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.187           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.085           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.494           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.567           ms/op
ClientSimple.getUser                        sample  15753   2.036 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.654           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.888           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.323           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.467           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.088           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.286           ms/op
ClientSimple.listUser                       sample   8956   3.574 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.106           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.671           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.131           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.034           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.721           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.721           ms/op

Benchmark result is saved to 1723077797076.json
