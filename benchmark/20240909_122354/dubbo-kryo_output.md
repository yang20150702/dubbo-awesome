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
# Warmup Iteration   1: 1.646 ops/ms
Iteration   1: 6.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.285 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.220 ops/ms
Iteration   1: 12.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.096 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ops/ms
Iteration   1: 11.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.059 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.524 ops/ms
Iteration   1: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.204 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.109 ms/op
Iteration   1: 2.196 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.196 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.817 ±(99.9%) 0.044 ms/op
Iteration   1: 1.995 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.995 ms/op


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.057 ms/op
Iteration   1: 2.152 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.152 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.915 ±(99.9%) 0.124 ms/op
Iteration   1: 3.593 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.593 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ±(99.9%) 0.106 ms/op
Iteration   1: 2.324 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   9.093 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 17.539 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13736
  mean =      2.324 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 10189 
    [ 2.500,  3.750) = 2827 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.539 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.082 ms/op
Iteration   1: 1.896 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.634 ms/op
                 existUser·p0.95:   2.896 ms/op
                 existUser·p0.99:   5.009 ms/op
                 existUser·p0.999:  13.929 ms/op
                 existUser·p0.9999: 14.450 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16862
  mean =      1.896 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1038 
    [ 1.250,  2.500) = 13637 
    [ 2.500,  3.750) = 1881 
    [ 3.750,  5.000) = 138 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      5.009 ms/op
     p(99.9000) =     13.929 ms/op
     p(99.9900) =     14.450 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.078 ms/op
Iteration   1: 2.134 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   2.021 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  11.927 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15029
  mean =      2.134 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 12737 
    [ 2.500,  3.750) = 1847 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     11.927 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.128 ms/op
Iteration   1: 3.364 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.199 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  12.034 ms/op
                 listUser·p0.9999: 12.075 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9502
  mean =      3.364 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1481 
    [ 2.500,  3.750) = 5098 
    [ 3.750,  5.000) = 2537 
    [ 5.000,  6.250) = 249 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     12.034 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     12.075 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.285          ops/ms
ClientSimple.existUser                       thrpt         12.096          ops/ms
ClientSimple.getUser                         thrpt         11.059          ops/ms
ClientSimple.listUser                        thrpt          9.204          ops/ms
ClientSimple.createUser                       avgt          2.196           ms/op
ClientSimple.existUser                        avgt          1.995           ms/op
ClientSimple.getUser                          avgt          2.152           ms/op
ClientSimple.listUser                         avgt          3.593           ms/op
ClientSimple.createUser                     sample  13736   2.324 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.657           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.174           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.093           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.007           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.539           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.662           ms/op
ClientSimple.existUser                      sample  16862   1.896 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.777           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.896           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.009           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.929           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.450           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.844           ms/op
ClientSimple.getUser                        sample  15029   2.134 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.504           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.021           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.350           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.927           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.173           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.173           ms/op
ClientSimple.listUser                       sample   9502   3.364 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.212           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.199           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.529           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.034           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.075           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.075           ms/op

Benchmark result is saved to 1725884374637.json
