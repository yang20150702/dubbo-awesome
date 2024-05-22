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
# Warmup Iteration   1: 1.435 ops/ms
Iteration   1: 6.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.048 ops/ms


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
# Warmup Iteration   1: 4.967 ops/ms
Iteration   1: 12.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.027 ops/ms


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
# Warmup Iteration   1: 4.761 ops/ms
Iteration   1: 11.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.548 ops/ms


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
# Warmup Iteration   1: 5.408 ops/ms
Iteration   1: 8.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.627 ops/ms


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.104 ms/op
Iteration   1: 2.128 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.128 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.057 ms/op
Iteration   1: 1.954 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.954 ms/op


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.088 ms/op
Iteration   1: 2.174 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.174 ms/op


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.118 ms/op
Iteration   1: 3.806 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.806 ms/op


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.107 ms/op
Iteration   1: 2.103 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 23.943 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15197
  mean =      2.103 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13060 
    [ 2.500,  5.000) = 1932 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     23.943 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.068 ms/op
Iteration   1: 1.931 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   1.812 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.183 ms/op
                 existUser·p0.999:  20.013 ms/op
                 existUser·p0.9999: 20.207 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16621
  mean =      1.931 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15500 
    [ 2.500,  5.000) = 1016 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.183 ms/op
     p(99.9000) =     20.013 ms/op
     p(99.9900) =     20.207 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.090 ms/op
Iteration   1: 2.082 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   1.939 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.761 ms/op
                 getUser·p0.99:   4.485 ms/op
                 getUser·p0.999:  35.848 ms/op
                 getUser·p0.9999: 36.206 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15353
  mean =      2.082 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13466 
    [ 2.500,  5.000) = 1755 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      4.485 ms/op
     p(99.9000) =     35.848 ms/op
     p(99.9900) =     36.206 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.120 ms/op
Iteration   1: 3.136 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.025 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 19.463 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10255
  mean =      3.136 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 2421 
    [ 2.500,  3.750) = 5773 
    [ 3.750,  5.000) = 1830 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.025 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     19.463 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.048          ops/ms
ClientSimple.existUser                       thrpt         12.027          ops/ms
ClientSimple.getUser                         thrpt         11.548          ops/ms
ClientSimple.listUser                        thrpt          8.627          ops/ms
ClientSimple.createUser                       avgt          2.128           ms/op
ClientSimple.existUser                        avgt          1.954           ms/op
ClientSimple.getUser                          avgt          2.174           ms/op
ClientSimple.listUser                         avgt          3.806           ms/op
ClientSimple.createUser                     sample  15197   2.103 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.963           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.062           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.547           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.943           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.216           ms/op
ClientSimple.existUser                      sample  16621   1.931 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.428           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.812           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.183           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.013           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.207           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.251           ms/op
ClientSimple.getUser                        sample  15353   2.082 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.578           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.939           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.485           ms/op
ClientSimple.getUser:getUser·p0.999         sample         35.848           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         36.206           ms/op
ClientSimple.getUser:getUser·p1.00          sample         36.241           ms/op
ClientSimple.listUser                       sample  10255   3.136 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.965           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.957           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.025           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.874           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.463           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.464           ms/op

Benchmark result is saved to 1716338359281.json
