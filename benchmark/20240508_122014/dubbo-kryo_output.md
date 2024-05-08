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
# Warmup Iteration   1: 1.564 ops/ms
Iteration   1: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.868 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.657 ops/ms
Iteration   1: 15.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.401 ops/ms


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
# Warmup Iteration   1: 5.834 ops/ms
Iteration   1: 12.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.683 ops/ms


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
# Warmup Iteration   1: 4.437 ops/ms
Iteration   1: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.726 ops/ms


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.089 ms/op
Iteration   1: 2.271 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.271 ms/op


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.064 ms/op
Iteration   1: 1.961 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.961 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.093 ms/op
Iteration   1: 2.171 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.171 ms/op


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
# Warmup Iteration   1: 5.275 ±(99.9%) 0.112 ms/op
Iteration   1: 3.158 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.158 ms/op


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.112 ms/op
Iteration   1: 2.109 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   5.507 ms/op
                 createUser·p0.999:  13.427 ms/op
                 createUser·p0.9999: 14.026 ms/op
                 createUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15476
  mean =      2.109 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 13375 
    [ 2.500,  3.750) = 1615 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      5.507 ms/op
     p(99.9000) =     13.427 ms/op
     p(99.9900) =     14.026 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 2.823 ±(99.9%) 0.069 ms/op
Iteration   1: 2.060 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.355 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   5.133 ms/op
                 existUser·p0.999:  30.015 ms/op
                 existUser·p0.9999: 30.616 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15569
  mean =      2.060 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13926 
    [ 2.500,  5.000) = 1480 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      5.133 ms/op
     p(99.9000) =     30.015 ms/op
     p(99.9900) =     30.616 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.088 ms/op
Iteration   1: 2.059 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   1.882 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   4.847 ms/op
                 getUser·p0.999:  13.234 ms/op
                 getUser·p0.9999: 14.145 ms/op
                 getUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15637
  mean =      2.059 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 13578 
    [ 2.500,  3.750) = 1782 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      4.847 ms/op
     p(99.9000) =     13.234 ms/op
     p(99.9900) =     14.145 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.161 ms/op
Iteration   1: 4.178 ±(99.9%) 0.068 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   8.425 ms/op
                 listUser·p0.999:  25.625 ms/op
                 listUser·p0.9999: 26.051 ms/op
                 listUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7674
  mean =      4.178 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182 
    [ 2.500,  5.000) = 7011 
    [ 5.000,  7.500) = 378 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      8.425 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.868          ops/ms
ClientSimple.existUser                       thrpt         15.401          ops/ms
ClientSimple.getUser                         thrpt         12.683          ops/ms
ClientSimple.listUser                        thrpt          7.726          ops/ms
ClientSimple.createUser                       avgt          2.271           ms/op
ClientSimple.existUser                        avgt          1.961           ms/op
ClientSimple.getUser                          avgt          2.171           ms/op
ClientSimple.listUser                         avgt          3.158           ms/op
ClientSimple.createUser                     sample  15476   2.109 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.504           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.507           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.427           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.026           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.107           ms/op
ClientSimple.existUser                      sample  15569   2.060 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.355           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.133           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.015           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.616           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.671           ms/op
ClientSimple.getUser                        sample  15637   2.059 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.890           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.882           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.847           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.234           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.145           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.238           ms/op
ClientSimple.listUser                       sample   7674   4.178 ± 0.068   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.159           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.006           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.425           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.625           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.051           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.051           ms/op

Benchmark result is saved to 1715170558733.json
