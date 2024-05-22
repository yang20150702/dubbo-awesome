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
# Warmup Iteration   1: 1.459 ops/ms
Iteration   1: 6.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.847 ops/ms


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
# Warmup Iteration   1: 5.281 ops/ms
Iteration   1: 11.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.678 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.560 ops/ms
Iteration   1: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.031 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ops/ms
Iteration   1: 7.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.455 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ±(99.9%) 0.057 ms/op
Iteration   1: 2.053 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.053 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ±(99.9%) 0.080 ms/op
Iteration   1: 1.927 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.927 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.074 ms/op
Iteration   1: 2.392 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.392 ms/op


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
# Warmup Iteration   1: 5.719 ±(99.9%) 0.133 ms/op
Iteration   1: 3.673 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.673 ms/op


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.112 ms/op
Iteration   1: 2.310 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.163 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   6.821 ms/op
                 createUser·p0.999:  18.771 ms/op
                 createUser·p0.9999: 19.893 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14165
  mean =      2.310 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 10540 
    [ 2.500,  3.750) = 3101 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      6.821 ms/op
     p(99.9000) =     18.771 ms/op
     p(99.9900) =     19.893 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.060 ±(99.9%) 0.075 ms/op
Iteration   1: 1.769 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.034 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   3.112 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 10.934 ms/op
                 existUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18223
  mean =      1.769 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 17529 
    [ 2.500,  3.750) = 254 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.034 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      3.112 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     10.934 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.092 ms/op
Iteration   1: 2.100 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   1.946 ms/op
                 getUser·p0.90:   2.695 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 12.256 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15266
  mean =      2.100 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 13168 
    [ 2.500,  3.750) = 1725 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     12.256 ms/op
     p(99.9990) =     12.403 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


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
# Warmup Iteration   1: 4.878 ±(99.9%) 0.147 ms/op
Iteration   1: 4.064 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   5.997 ms/op
                 listUser·p0.999:  40.674 ms/op
                 listUser·p0.9999: 41.812 ms/op
                 listUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7871
  mean =      4.064 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7533 
    [ 5.000, 10.000) = 304 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     40.674 ms/op
     p(99.9900) =     41.812 ms/op
     p(99.9990) =     41.812 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.847          ops/ms
ClientSimple.existUser                       thrpt         11.678          ops/ms
ClientSimple.getUser                         thrpt         13.031          ops/ms
ClientSimple.listUser                        thrpt          7.455          ops/ms
ClientSimple.createUser                       avgt          2.053           ms/op
ClientSimple.existUser                        avgt          1.927           ms/op
ClientSimple.getUser                          avgt          2.392           ms/op
ClientSimple.listUser                         avgt          3.673           ms/op
ClientSimple.createUser                     sample  14165   2.310 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.873           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.163           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.129           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.821           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.771           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.893           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  18223   1.769 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.475           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.034           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.112           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.764           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.934           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.961           ms/op
ClientSimple.getUser                        sample  15266   2.100 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.598           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.946           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.142           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.833           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.862           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.256           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.403           ms/op
ClientSimple.listUser                       sample   7871   4.064 ± 0.090   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.225           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.997           ms/op
ClientSimple.listUser:listUser·p0.999       sample         40.674           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         41.812           ms/op
ClientSimple.listUser:listUser·p1.00        sample         41.812           ms/op

Benchmark result is saved to 1716380186659.json
