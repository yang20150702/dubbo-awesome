# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.382 ops/ms
Iteration   1: 5.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.680 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.817 ops/ms
Iteration   1: 13.347 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.347 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ops/ms
Iteration   1: 7.816 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.816 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.190 ops/ms
Iteration   1: 3.622 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.622 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.600 ±(99.9%) 0.080 ms/op
Iteration   1: 3.183 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ±(99.9%) 0.088 ms/op
Iteration   1: 2.002 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.002 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.874 ±(99.9%) 0.054 ms/op
Iteration   1: 2.773 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 14.303 ±(99.9%) 0.373 ms/op
Iteration   1: 10.127 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.237 ±(99.9%) 0.130 ms/op
Iteration   1: 3.242 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  12.285 ms/op
                 createUser·p0.9999: 15.974 ms/op
                 createUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9863
  mean =      3.242 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 615 
    [ 2.500,  3.750) = 7973 
    [ 3.750,  5.000) = 752 
    [ 5.000,  6.250) = 279 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     12.285 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ±(99.9%) 0.069 ms/op
Iteration   1: 1.888 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.044 ms/op
                 existUser·p0.999:  23.462 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16985
  mean =      1.888 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16297 
    [ 2.500,  5.000) = 607 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.044 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ±(99.9%) 0.135 ms/op
Iteration   1: 3.187 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  11.337 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10022
  mean =      3.187 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1176 
    [ 2.500,  3.750) = 7315 
    [ 3.750,  5.000) = 1272 
    [ 5.000,  6.250) = 183 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     11.337 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.932 ±(99.9%) 0.678 ms/op
Iteration   1: 8.665 ±(99.9%) 0.134 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   8.348 ms/op
                 listUser·p0.90:   10.953 ms/op
                 listUser·p0.95:   12.157 ms/op
                 listUser·p0.99:   17.205 ms/op
                 listUser·p0.999:  30.642 ms/op
                 listUser·p0.9999: 38.076 ms/op
                 listUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3694
  mean =      8.665 ±(99.9%) 0.134 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 37 
    [ 5.000,  7.500) = 1100 
    [ 7.500, 10.000) = 1866 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.499 ms/op
     p(50.0000) =      8.348 ms/op
     p(90.0000) =     10.953 ms/op
     p(95.0000) =     12.157 ms/op
     p(99.0000) =     17.205 ms/op
     p(99.9000) =     30.642 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.680          ops/ms
Client.existUser                       thrpt         13.347          ops/ms
Client.getUser                         thrpt          7.816          ops/ms
Client.listUser                        thrpt          3.622          ops/ms
Client.createUser                       avgt          3.183           ms/op
Client.existUser                        avgt          2.002           ms/op
Client.getUser                          avgt          2.773           ms/op
Client.listUser                         avgt         10.127           ms/op
Client.createUser                     sample   9863   3.242 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.257           ms/op
Client.createUser:createUser·p0.50    sample          2.937           ms/op
Client.createUser:createUser·p0.90    sample          4.219           ms/op
Client.createUser:createUser·p0.95    sample          5.071           ms/op
Client.createUser:createUser·p0.99    sample          9.585           ms/op
Client.createUser:createUser·p0.999   sample         12.285           ms/op
Client.createUser:createUser·p0.9999  sample         15.974           ms/op
Client.createUser:createUser·p1.00    sample         15.974           ms/op
Client.existUser                      sample  16985   1.888 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.788           ms/op
Client.existUser:existUser·p0.50      sample          1.796           ms/op
Client.existUser:existUser·p0.90      sample          2.302           ms/op
Client.existUser:existUser·p0.95      sample          2.445           ms/op
Client.existUser:existUser·p0.99      sample          3.044           ms/op
Client.existUser:existUser·p0.999     sample         23.462           ms/op
Client.existUser:existUser·p0.9999    sample         24.379           ms/op
Client.existUser:existUser·p1.00      sample         24.379           ms/op
Client.getUser                        sample  10022   3.187 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.041           ms/op
Client.getUser:getUser·p0.50          sample          3.043           ms/op
Client.getUser:getUser·p0.90          sample          3.924           ms/op
Client.getUser:getUser·p0.95          sample          4.334           ms/op
Client.getUser:getUser·p0.99          sample          5.833           ms/op
Client.getUser:getUser·p0.999         sample         11.337           ms/op
Client.getUser:getUser·p0.9999        sample         11.665           ms/op
Client.getUser:getUser·p1.00          sample         11.665           ms/op
Client.listUser                       sample   3694   8.665 ± 0.134   ms/op
Client.listUser:listUser·p0.00        sample          2.499           ms/op
Client.listUser:listUser·p0.50        sample          8.348           ms/op
Client.listUser:listUser·p0.90        sample         10.953           ms/op
Client.listUser:listUser·p0.95        sample         12.157           ms/op
Client.listUser:listUser·p0.99        sample         17.205           ms/op
Client.listUser:listUser·p0.999       sample         30.642           ms/op
Client.listUser:listUser·p0.9999      sample         38.076           ms/op
Client.listUser:listUser·p1.00        sample         38.076           ms/op
