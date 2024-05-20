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
# Warmup Iteration   1: 1.515 ops/ms
Iteration   1: 7.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.307 ops/ms


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
# Warmup Iteration   1: 5.931 ops/ms
Iteration   1: 12.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.320 ops/ms


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
# Warmup Iteration   1: 4.473 ops/ms
Iteration   1: 12.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.331 ops/ms


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
# Warmup Iteration   1: 5.396 ops/ms
Iteration   1: 9.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.008 ops/ms


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.064 ms/op
Iteration   1: 2.214 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.214 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.051 ms/op
Iteration   1: 1.905 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.067 ms/op
Iteration   1: 1.890 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.890 ms/op


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.096 ms/op
Iteration   1: 3.294 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.294 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.116 ms/op
Iteration   1: 2.240 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   12.599 ms/op
                 createUser·p0.999:  21.977 ms/op
                 createUser·p0.9999: 25.991 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14327
  mean =      2.240 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12842 
    [ 2.500,  5.000) = 1140 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     21.977 ms/op
     p(99.9900) =     25.991 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 3.032 ±(99.9%) 0.076 ms/op
Iteration   1: 2.089 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   1.995 ms/op
                 existUser·p0.90:   2.654 ms/op
                 existUser·p0.95:   2.892 ms/op
                 existUser·p0.99:   3.509 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 15.141 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15329
  mean =      2.089 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 241 
    [ 1.250,  2.500) = 12259 
    [ 2.500,  3.750) = 2717 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      3.509 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     15.141 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.096 ms/op
Iteration   1: 1.954 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   1.788 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  19.417 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16441
  mean =      1.954 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 15098 
    [ 2.500,  3.750) = 1060 
    [ 3.750,  5.000) = 149 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =     19.417 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.316 ±(99.9%) 0.129 ms/op
Iteration   1: 3.486 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.184 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.095 ms/op
                 listUser·p0.999:  9.953 ms/op
                 listUser·p0.9999: 12.075 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9174
  mean =      3.486 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 951 
    [ 2.500,  3.750) = 4998 
    [ 3.750,  5.000) = 2886 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.184 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =      9.953 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     12.075 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.307          ops/ms
ClientSimple.existUser                       thrpt         12.320          ops/ms
ClientSimple.getUser                         thrpt         12.331          ops/ms
ClientSimple.listUser                        thrpt          9.008          ops/ms
ClientSimple.createUser                       avgt          2.214           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          1.890           ms/op
ClientSimple.listUser                         avgt          3.294           ms/op
ClientSimple.createUser                     sample  14327   2.240 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.623           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.599           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.977           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.991           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.345           ms/op
ClientSimple.existUser                      sample  15329   2.089 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.595           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.995           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.892           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.509           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.877           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.141           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.368           ms/op
ClientSimple.getUser                        sample  16441   1.954 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.519           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.788           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.145           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.417           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.825           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.825           ms/op
ClientSimple.listUser                       sample   9174   3.486 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.184           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.095           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.953           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.075           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.075           ms/op

Benchmark result is saved to 1716165599204.json
