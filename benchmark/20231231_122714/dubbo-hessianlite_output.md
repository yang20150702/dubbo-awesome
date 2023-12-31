# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.205 ops/ms
Iteration   1: 5.758 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.758 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.213 ops/ms
Iteration   1: 13.849 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.849 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ops/ms
Iteration   1: 7.765 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.765 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.863 ops/ms
Iteration   1: 3.435 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.435 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.643 ±(99.9%) 0.077 ms/op
Iteration   1: 3.271 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.271 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ±(99.9%) 0.042 ms/op
Iteration   1: 1.970 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ±(99.9%) 0.064 ms/op
Iteration   1: 3.281 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.291 ±(99.9%) 0.251 ms/op
Iteration   1: 8.990 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ±(99.9%) 0.106 ms/op
Iteration   1: 2.923 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   7.502 ms/op
                 createUser·p0.999:  15.484 ms/op
                 createUser·p0.9999: 15.589 ms/op
                 createUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10920
  mean =      2.923 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 3354 
    [ 2.500,  3.750) = 6727 
    [ 3.750,  5.000) = 530 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      7.502 ms/op
     p(99.9000) =     15.484 ms/op
     p(99.9900) =     15.589 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ±(99.9%) 0.068 ms/op
Iteration   1: 1.871 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.201 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 19.020 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17083
  mean =      1.871 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 317 
    [ 1.250,  2.500) = 15969 
    [ 2.500,  3.750) = 654 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.201 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.020 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.109 ms/op
Iteration   1: 3.400 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  15.260 ms/op
                 getUser·p0.9999: 16.269 ms/op
                 getUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9597
  mean =      3.400 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1095 
    [ 2.500,  3.750) = 5921 
    [ 3.750,  5.000) = 2354 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.260 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.743 ±(99.9%) 0.423 ms/op
Iteration   1: 9.036 ±(99.9%) 0.150 ms/op
                 listUser·p0.00:   3.895 ms/op
                 listUser·p0.50:   8.405 ms/op
                 listUser·p0.90:   12.049 ms/op
                 listUser·p0.95:   13.615 ms/op
                 listUser·p0.99:   20.547 ms/op
                 listUser·p0.999:  24.424 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3547
  mean =      9.036 ±(99.9%) 0.150 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 33 
    [ 5.000,  7.500) = 1013 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 674 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.895 ms/op
     p(50.0000) =      8.405 ms/op
     p(90.0000) =     12.049 ms/op
     p(95.0000) =     13.615 ms/op
     p(99.0000) =     20.547 ms/op
     p(99.9000) =     24.424 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.758          ops/ms
Client.existUser                       thrpt         13.849          ops/ms
Client.getUser                         thrpt          7.765          ops/ms
Client.listUser                        thrpt          3.435          ops/ms
Client.createUser                       avgt          3.271           ms/op
Client.existUser                        avgt          1.970           ms/op
Client.getUser                          avgt          3.281           ms/op
Client.listUser                         avgt          8.990           ms/op
Client.createUser                     sample  10920   2.923 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.147           ms/op
Client.createUser:createUser·p0.50    sample          2.675           ms/op
Client.createUser:createUser·p0.90    sample          3.510           ms/op
Client.createUser:createUser·p0.95    sample          4.178           ms/op
Client.createUser:createUser·p0.99    sample          7.502           ms/op
Client.createUser:createUser·p0.999   sample         15.484           ms/op
Client.createUser:createUser·p0.9999  sample         15.589           ms/op
Client.createUser:createUser·p1.00    sample         15.598           ms/op
Client.existUser                      sample  17083   1.871 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.819           ms/op
Client.existUser:existUser·p0.50      sample          1.772           ms/op
Client.existUser:existUser·p0.90      sample          2.314           ms/op
Client.existUser:existUser·p0.95      sample          2.482           ms/op
Client.existUser:existUser·p0.99      sample          3.201           ms/op
Client.existUser:existUser·p0.999     sample         18.940           ms/op
Client.existUser:existUser·p0.9999    sample         19.020           ms/op
Client.existUser:existUser·p1.00      sample         19.137           ms/op
Client.getUser                        sample   9597   3.400 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          1.169           ms/op
Client.getUser:getUser·p0.50          sample          3.396           ms/op
Client.getUser:getUser·p0.90          sample          4.162           ms/op
Client.getUser:getUser·p0.95          sample          4.440           ms/op
Client.getUser:getUser·p0.99          sample          5.595           ms/op
Client.getUser:getUser·p0.999         sample         15.260           ms/op
Client.getUser:getUser·p0.9999        sample         16.269           ms/op
Client.getUser:getUser·p1.00          sample         16.269           ms/op
Client.listUser                       sample   3547   9.036 ± 0.150   ms/op
Client.listUser:listUser·p0.00        sample          3.895           ms/op
Client.listUser:listUser·p0.50        sample          8.405           ms/op
Client.listUser:listUser·p0.90        sample         12.049           ms/op
Client.listUser:listUser·p0.95        sample         13.615           ms/op
Client.listUser:listUser·p0.99        sample         20.547           ms/op
Client.listUser:listUser·p0.999       sample         24.424           ms/op
Client.listUser:listUser·p0.9999      sample         26.116           ms/op
Client.listUser:listUser·p1.00        sample         26.116           ms/op
