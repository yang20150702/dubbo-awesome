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
# Warmup Iteration   1: 1.852 ops/ms
Iteration   1: 6.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.485 ops/ms


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
# Warmup Iteration   1: 6.241 ops/ms
Iteration   1: 12.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.348 ops/ms


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
# Warmup Iteration   1: 5.296 ops/ms
Iteration   1: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.688 ops/ms


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
# Warmup Iteration   1: 4.509 ops/ms
Iteration   1: 8.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.854 ops/ms


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.069 ms/op
Iteration   1: 2.378 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.378 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.060 ms/op
Iteration   1: 1.996 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.996 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.070 ms/op
Iteration   1: 2.093 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.093 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.119 ms/op
Iteration   1: 3.588 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.588 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.091 ms/op
Iteration   1: 2.188 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.732 ms/op
                 createUser·p0.95:   2.957 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  30.537 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14613
  mean =      2.188 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11333 
    [ 2.500,  5.000) = 3058 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     30.537 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.079 ms/op
Iteration   1: 1.751 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   4.027 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 19.508 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18279
  mean =      1.751 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1464 
    [ 1.250,  2.500) = 16152 
    [ 2.500,  3.750) = 455 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      4.027 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.508 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.079 ms/op
Iteration   1: 1.978 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.275 ms/op
                 getUser·p0.95:   2.515 ms/op
                 getUser·p0.99:   3.884 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 13.353 ms/op
                 getUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16194
  mean =      1.978 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 15299 
    [ 2.500,  3.750) = 681 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.275 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      3.884 ms/op
     p(99.9000) =     11.551 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.142 ms/op
Iteration   1: 3.923 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.789 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8157
  mean =      3.923 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 544 
    [ 2.500,  3.750) = 3215 
    [ 3.750,  5.000) = 3410 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.789 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.485          ops/ms
ClientSimple.existUser                       thrpt         12.348          ops/ms
ClientSimple.getUser                         thrpt         12.688          ops/ms
ClientSimple.listUser                        thrpt          8.854          ops/ms
ClientSimple.createUser                       avgt          2.378           ms/op
ClientSimple.existUser                        avgt          1.996           ms/op
ClientSimple.getUser                          avgt          2.093           ms/op
ClientSimple.listUser                         avgt          3.588           ms/op
ClientSimple.createUser                     sample  14613   2.188 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.526           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.634           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.537           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.751           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.751           ms/op
ClientSimple.existUser                      sample  18279   1.751 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.597           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.027           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.508           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.562           ms/op
ClientSimple.getUser                        sample  16194   1.978 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.036           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.275           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.884           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.551           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.353           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.434           ms/op
ClientSimple.listUser                       sample   8157   3.923 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.333           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.858           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.128           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.789           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.334           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.071           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.071           ms/op

Benchmark result is saved to 1716293758709.json
