# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.934 ops/ms
Iteration   1: 7.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.453 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.752 ops/ms
Iteration   1: 13.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.818 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.730 ops/ms
Iteration   1: 12.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.355 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.509 ops/ms
Iteration   1: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.177 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.074 ms/op
Iteration   1: 2.168 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.168 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.910 ±(99.9%) 0.040 ms/op
Iteration   1: 1.665 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.665 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.117 ±(99.9%) 0.052 ms/op
Iteration   1: 2.098 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.098 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.094 ms/op
Iteration   1: 3.171 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.171 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ±(99.9%) 0.081 ms/op
Iteration   1: 2.326 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   2.777 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   6.844 ms/op
                 createUser·p0.999:  15.606 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13780
  mean =      2.326 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 10386 
    [ 2.500,  3.750) = 3010 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      6.844 ms/op
     p(99.9000) =     15.606 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.006 ±(99.9%) 0.064 ms/op
Iteration   1: 1.919 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.808 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.265 ms/op
                 existUser·p0.999:  23.474 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16643
  mean =      1.919 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15600 
    [ 2.500,  5.000) = 896 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.265 ms/op
     p(99.9000) =     23.474 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.175 ±(99.9%) 0.082 ms/op
Iteration   1: 2.016 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   1.935 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.580 ms/op
                 getUser·p0.99:   4.180 ms/op
                 getUser·p0.999:  13.451 ms/op
                 getUser·p0.9999: 14.165 ms/op
                 getUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16015
  mean =      2.016 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 14917 
    [ 2.500,  3.750) = 780 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.180 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     14.165 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.459 ±(99.9%) 0.145 ms/op
Iteration   1: 3.159 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.421 ms/op
                 listUser·p0.99:   6.002 ms/op
                 listUser·p0.999:  6.871 ms/op
                 listUser·p0.9999: 7.329 ms/op
                 listUser·p1.00:   7.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10126
  mean =      3.159 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 134 
    [2.000, 2.500) = 2160 
    [2.500, 3.000) = 3121 
    [3.000, 3.500) = 1194 
    [3.500, 4.000) = 1932 
    [4.000, 4.500) = 1114 
    [4.500, 5.000) = 216 
    [5.000, 5.500) = 97 
    [5.500, 6.000) = 42 
    [6.000, 6.500) = 58 
    [6.500, 7.000) = 41 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.421 ms/op
     p(99.0000) =      6.002 ms/op
     p(99.9000) =      6.871 ms/op
     p(99.9900) =      7.329 ms/op
     p(99.9990) =      7.332 ms/op
     p(99.9999) =      7.332 ms/op
    p(100.0000) =      7.332 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.453          ops/ms
ClientSimple.existUser                       thrpt         13.818          ops/ms
ClientSimple.getUser                         thrpt         12.355          ops/ms
ClientSimple.listUser                        thrpt          9.177          ops/ms
ClientSimple.createUser                       avgt          2.168           ms/op
ClientSimple.existUser                        avgt          1.665           ms/op
ClientSimple.getUser                          avgt          2.098           ms/op
ClientSimple.listUser                         avgt          3.171           ms/op
ClientSimple.createUser                     sample  13780   2.326 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.844           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.606           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.941           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.941           ms/op
ClientSimple.existUser                      sample  16643   1.919 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.535           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.808           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.265           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.474           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.642           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.707           ms/op
ClientSimple.getUser                        sample  16015   2.016 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.456           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.935           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.180           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.451           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.165           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.402           ms/op
ClientSimple.listUser                       sample  10126   3.159 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.929           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.884           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.421           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.002           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.871           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.329           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.332           ms/op

Benchmark result is saved to 1713679945714.json
