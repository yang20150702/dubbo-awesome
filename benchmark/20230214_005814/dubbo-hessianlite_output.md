# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.034 ops/ms
Iteration   1: 2.466 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.466 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ops/ms
Iteration   1: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.903 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.126 ops/ms
Iteration   1: 4.710 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.710 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.993 ops/ms
Iteration   1: 1.406 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.406 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 13.768 ±(99.9%) 0.236 ms/op
Iteration   1: 8.099 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.064 ms/op
Iteration   1: 3.761 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.334 ±(99.9%) 0.101 ms/op
Iteration   1: 4.558 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.558 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.943 ±(99.9%) 0.422 ms/op
Iteration   1: 17.485 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.485 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.178 ±(99.9%) 0.374 ms/op
Iteration   1: 5.784 ±(99.9%) 0.094 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   6.234 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   13.238 ms/op
                 createUser·p0.999:  18.756 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5607
  mean =      5.784 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 566 
    [ 2.500,  3.750) = 477 
    [ 3.750,  5.000) = 302 
    [ 5.000,  6.250) = 1500 
    [ 6.250,  7.500) = 2466 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     13.238 ms/op
     p(99.9000) =     18.756 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.576 ±(99.9%) 0.201 ms/op
Iteration   1: 2.939 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.381 ms/op
                 existUser·p0.95:   4.934 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  13.813 ms/op
                 existUser·p0.9999: 14.055 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10904
  mean =      2.939 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 2228 
    [ 2.500,  3.750) = 7683 
    [ 3.750,  5.000) = 322 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.381 ms/op
     p(95.0000) =      4.934 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     13.813 ms/op
     p(99.9900) =     14.055 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.279 ±(99.9%) 0.340 ms/op
Iteration   1: 4.564 ±(99.9%) 0.081 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   7.074 ms/op
                 getUser·p0.95:   8.864 ms/op
                 getUser·p0.99:   12.337 ms/op
                 getUser·p0.999:  16.876 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7074
  mean =      4.564 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 253 
    [ 2.500,  3.750) = 2719 
    [ 3.750,  5.000) = 2172 
    [ 5.000,  6.250) = 969 
    [ 6.250,  7.500) = 358 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 150 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      7.074 ms/op
     p(95.0000) =      8.864 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.171 ±(99.9%) 0.814 ms/op
Iteration   1: 14.188 ±(99.9%) 0.209 ms/op
                 listUser·p0.00:   5.022 ms/op
                 listUser·p0.50:   13.353 ms/op
                 listUser·p0.90:   17.891 ms/op
                 listUser·p0.95:   20.709 ms/op
                 listUser·p0.99:   26.117 ms/op
                 listUser·p0.999:  30.303 ms/op
                 listUser·p0.9999: 30.409 ms/op
                 listUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2248
  mean =     14.188 ±(99.9%) 0.209 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 622 
    [12.500, 15.000) = 1087 
    [15.000, 17.500) = 284 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.022 ms/op
     p(50.0000) =     13.353 ms/op
     p(90.0000) =     17.891 ms/op
     p(95.0000) =     20.709 ms/op
     p(99.0000) =     26.117 ms/op
     p(99.9000) =     30.303 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.466          ops/ms
Client.existUser                       thrpt          7.903          ops/ms
Client.getUser                         thrpt          4.710          ops/ms
Client.listUser                        thrpt          1.406          ops/ms
Client.createUser                       avgt          8.099           ms/op
Client.existUser                        avgt          3.761           ms/op
Client.getUser                          avgt          4.558           ms/op
Client.listUser                         avgt         17.485           ms/op
Client.createUser                     sample   5607   5.784 ± 0.094   ms/op
Client.createUser:createUser·p0.00    sample          1.239           ms/op
Client.createUser:createUser·p0.50    sample          6.234           ms/op
Client.createUser:createUser·p0.90    sample          7.111           ms/op
Client.createUser:createUser·p0.95    sample          7.799           ms/op
Client.createUser:createUser·p0.99    sample         13.238           ms/op
Client.createUser:createUser·p0.999   sample         18.756           ms/op
Client.createUser:createUser·p0.9999  sample         18.907           ms/op
Client.createUser:createUser·p1.00    sample         18.907           ms/op
Client.existUser                      sample  10904   2.939 ± 0.042   ms/op
Client.existUser:existUser·p0.00      sample          0.786           ms/op
Client.existUser:existUser·p0.50      sample          2.810           ms/op
Client.existUser:existUser·p0.90      sample          3.381           ms/op
Client.existUser:existUser·p0.95      sample          4.934           ms/op
Client.existUser:existUser·p0.99      sample          9.585           ms/op
Client.existUser:existUser·p0.999     sample         13.813           ms/op
Client.existUser:existUser·p0.9999    sample         14.055           ms/op
Client.existUser:existUser·p1.00      sample         14.057           ms/op
Client.getUser                        sample   7074   4.564 ± 0.081   ms/op
Client.getUser:getUser·p0.00          sample          1.106           ms/op
Client.getUser:getUser·p0.50          sample          4.030           ms/op
Client.getUser:getUser·p0.90          sample          7.074           ms/op
Client.getUser:getUser·p0.95          sample          8.864           ms/op
Client.getUser:getUser·p0.99          sample         12.337           ms/op
Client.getUser:getUser·p0.999         sample         16.876           ms/op
Client.getUser:getUser·p0.9999        sample         16.876           ms/op
Client.getUser:getUser·p1.00          sample         16.876           ms/op
Client.listUser                       sample   2248  14.188 ± 0.209   ms/op
Client.listUser:listUser·p0.00        sample          5.022           ms/op
Client.listUser:listUser·p0.50        sample         13.353           ms/op
Client.listUser:listUser·p0.90        sample         17.891           ms/op
Client.listUser:listUser·p0.95        sample         20.709           ms/op
Client.listUser:listUser·p0.99        sample         26.117           ms/op
Client.listUser:listUser·p0.999       sample         30.303           ms/op
Client.listUser:listUser·p0.9999      sample         30.409           ms/op
Client.listUser:listUser·p1.00        sample         30.409           ms/op
