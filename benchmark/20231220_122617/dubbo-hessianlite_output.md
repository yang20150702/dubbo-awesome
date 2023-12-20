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
# Warmup Iteration   1: 2.330 ops/ms
Iteration   1: 6.458 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.458 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.594 ops/ms
Iteration   1: 13.445 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.445 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.349 ops/ms
Iteration   1: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.062 ops/ms


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
# Warmup Iteration   1: 1.893 ops/ms
Iteration   1: 2.947 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.947 ops/ms


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.080 ms/op
Iteration   1: 3.182 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.182 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.029 ms/op
Iteration   1: 2.050 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.050 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.057 ms/op
Iteration   1: 3.186 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.186 ms/op


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
# Warmup Iteration   1: 12.887 ±(99.9%) 0.278 ms/op
Iteration   1: 8.728 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.728 ms/op


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
# Warmup Iteration   1: 5.258 ±(99.9%) 0.117 ms/op
Iteration   1: 2.923 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.773 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.962 ms/op
                 createUser·p0.99:   7.132 ms/op
                 createUser·p0.999:  14.896 ms/op
                 createUser·p0.9999: 18.937 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10911
  mean =      2.923 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 2657 
    [ 2.500,  3.750) = 7613 
    [ 3.750,  5.000) = 373 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.962 ms/op
     p(99.0000) =      7.132 ms/op
     p(99.9000) =     14.896 ms/op
     p(99.9900) =     18.937 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.016 ±(99.9%) 0.063 ms/op
Iteration   1: 1.918 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  14.303 ms/op
                 existUser·p0.9999: 16.311 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16760
  mean =      1.918 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 15050 
    [ 2.500,  3.750) = 1240 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     16.311 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.111 ms/op
Iteration   1: 3.489 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.455 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  9.842 ms/op
                 getUser·p0.9999: 9.961 ms/op
                 getUser·p1.00:   9.961 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9160
  mean =      3.489 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 58 
    [ 2.000,  3.000) = 2223 
    [ 3.000,  4.000) = 5146 
    [ 4.000,  5.000) = 1492 
    [ 5.000,  6.000) = 192 
    [ 6.000,  7.000) = 10 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.455 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.842 ms/op
     p(99.9900) =      9.961 ms/op
     p(99.9990) =      9.961 ms/op
     p(99.9999) =      9.961 ms/op
    p(100.0000) =      9.961 ms/op


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
# Warmup Iteration   1: 12.214 ±(99.9%) 0.426 ms/op
Iteration   1: 8.611 ±(99.9%) 0.169 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   8.307 ms/op
                 listUser·p0.90:   11.469 ms/op
                 listUser·p0.95:   12.943 ms/op
                 listUser·p0.99:   17.251 ms/op
                 listUser·p0.999:  33.614 ms/op
                 listUser·p0.9999: 34.931 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3804
  mean =      8.611 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 234 
    [ 5.000,  7.500) = 1083 
    [ 7.500, 10.000) = 1636 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      8.307 ms/op
     p(90.0000) =     11.469 ms/op
     p(95.0000) =     12.943 ms/op
     p(99.0000) =     17.251 ms/op
     p(99.9000) =     33.614 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.458          ops/ms
Client.existUser                       thrpt         13.445          ops/ms
Client.getUser                         thrpt          8.062          ops/ms
Client.listUser                        thrpt          2.947          ops/ms
Client.createUser                       avgt          3.182           ms/op
Client.existUser                        avgt          2.050           ms/op
Client.getUser                          avgt          3.186           ms/op
Client.listUser                         avgt          8.728           ms/op
Client.createUser                     sample  10911   2.923 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.071           ms/op
Client.createUser:createUser·p0.50    sample          2.773           ms/op
Client.createUser:createUser·p0.90    sample          3.367           ms/op
Client.createUser:createUser·p0.95    sample          3.962           ms/op
Client.createUser:createUser·p0.99    sample          7.132           ms/op
Client.createUser:createUser·p0.999   sample         14.896           ms/op
Client.createUser:createUser·p0.9999  sample         18.937           ms/op
Client.createUser:createUser·p1.00    sample         18.940           ms/op
Client.existUser                      sample  16760   1.918 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.587           ms/op
Client.existUser:existUser·p0.50      sample          1.794           ms/op
Client.existUser:existUser·p0.90      sample          2.445           ms/op
Client.existUser:existUser·p0.95      sample          2.658           ms/op
Client.existUser:existUser·p0.99      sample          3.535           ms/op
Client.existUser:existUser·p0.999     sample         14.303           ms/op
Client.existUser:existUser·p0.9999    sample         16.311           ms/op
Client.existUser:existUser·p1.00      sample         18.383           ms/op
Client.getUser                        sample   9160   3.489 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.724           ms/op
Client.getUser:getUser·p0.50          sample          3.455           ms/op
Client.getUser:getUser·p0.90          sample          4.252           ms/op
Client.getUser:getUser·p0.95          sample          4.628           ms/op
Client.getUser:getUser·p0.99          sample          5.497           ms/op
Client.getUser:getUser·p0.999         sample          9.842           ms/op
Client.getUser:getUser·p0.9999        sample          9.961           ms/op
Client.getUser:getUser·p1.00          sample          9.961           ms/op
Client.listUser                       sample   3804   8.611 ± 0.169   ms/op
Client.listUser:listUser·p0.00        sample          2.187           ms/op
Client.listUser:listUser·p0.50        sample          8.307           ms/op
Client.listUser:listUser·p0.90        sample         11.469           ms/op
Client.listUser:listUser·p0.95        sample         12.943           ms/op
Client.listUser:listUser·p0.99        sample         17.251           ms/op
Client.listUser:listUser·p0.999       sample         33.614           ms/op
Client.listUser:listUser·p0.9999      sample         34.931           ms/op
Client.listUser:listUser·p1.00        sample         34.931           ms/op
