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
# Warmup Iteration   1: 2.773 ops/ms
Iteration   1: 5.320 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.320 ops/ms


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
# Warmup Iteration   1: 7.339 ops/ms
Iteration   1: 16.443 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  16.443 ops/ms


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
# Warmup Iteration   1: 4.357 ops/ms
Iteration   1: 8.481 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.481 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
Iteration   1: 4.226 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.226 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.210 ±(99.9%) 0.063 ms/op
Iteration   1: 3.634 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.634 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.146 ±(99.9%) 0.032 ms/op
Iteration   1: 1.900 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.900 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ±(99.9%) 0.042 ms/op
Iteration   1: 2.972 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.972 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.102 ±(99.9%) 0.358 ms/op
Iteration   1: 7.834 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.834 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.085 ms/op
Iteration   1: 3.171 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.291 ms/op
                 createUser·p0.99:   6.442 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 16.437 ms/op
                 createUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10082
  mean =      3.171 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1726 
    [ 2.500,  3.750) = 7007 
    [ 3.750,  5.000) = 1030 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.291 ms/op
     p(99.0000) =      6.442 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     16.437 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ±(99.9%) 0.058 ms/op
Iteration   1: 1.832 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   1.777 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   3.329 ms/op
                 existUser·p0.999:  15.057 ms/op
                 existUser·p0.9999: 16.597 ms/op
                 existUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17476
  mean =      1.832 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 561 
    [ 1.250,  2.500) = 16196 
    [ 2.500,  3.750) = 609 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.777 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.329 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.085 ms/op
Iteration   1: 3.370 ±(99.9%) 0.102 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   12.125 ms/op
                 getUser·p0.999:  51.020 ms/op
                 getUser·p0.9999: 53.805 ms/op
                 getUser·p1.00:   53.805 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9495
  mean =      3.370 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9183 
    [ 5.000, 10.000) = 185 
    [10.000, 15.000) = 95 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =     12.125 ms/op
     p(99.9000) =     51.020 ms/op
     p(99.9900) =     53.805 ms/op
     p(99.9990) =     53.805 ms/op
     p(99.9999) =     53.805 ms/op
    p(100.0000) =     53.805 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.282 ±(99.9%) 0.368 ms/op
Iteration   1: 8.587 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   8.331 ms/op
                 listUser·p0.90:   11.452 ms/op
                 listUser·p0.95:   12.452 ms/op
                 listUser·p0.99:   15.506 ms/op
                 listUser·p0.999:  21.949 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3742
  mean =      8.587 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 82 
    [ 5.000,  7.500) = 1097 
    [ 7.500, 10.000) = 1758 
    [10.000, 12.500) = 622 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      8.331 ms/op
     p(90.0000) =     11.452 ms/op
     p(95.0000) =     12.452 ms/op
     p(99.0000) =     15.506 ms/op
     p(99.9000) =     21.949 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.320          ops/ms
Client.existUser                       thrpt         16.443          ops/ms
Client.getUser                         thrpt          8.481          ops/ms
Client.listUser                        thrpt          4.226          ops/ms
Client.createUser                       avgt          3.634           ms/op
Client.existUser                        avgt          1.900           ms/op
Client.getUser                          avgt          2.972           ms/op
Client.listUser                         avgt          7.834           ms/op
Client.createUser                     sample  10082   3.171 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.313           ms/op
Client.createUser:createUser·p0.50    sample          3.076           ms/op
Client.createUser:createUser·p0.90    sample          3.863           ms/op
Client.createUser:createUser·p0.95    sample          4.291           ms/op
Client.createUser:createUser·p0.99    sample          6.442           ms/op
Client.createUser:createUser·p0.999   sample         14.254           ms/op
Client.createUser:createUser·p0.9999  sample         16.437           ms/op
Client.createUser:createUser·p1.00    sample         16.450           ms/op
Client.existUser                      sample  17476   1.832 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.475           ms/op
Client.existUser:existUser·p0.50      sample          1.777           ms/op
Client.existUser:existUser·p0.90      sample          2.228           ms/op
Client.existUser:existUser·p0.95      sample          2.408           ms/op
Client.existUser:existUser·p0.99      sample          3.329           ms/op
Client.existUser:existUser·p0.999     sample         15.057           ms/op
Client.existUser:existUser·p0.9999    sample         16.597           ms/op
Client.existUser:existUser·p1.00      sample         16.597           ms/op
Client.getUser                        sample   9495   3.370 ± 0.102   ms/op
Client.getUser:getUser·p0.00          sample          0.633           ms/op
Client.getUser:getUser·p0.50          sample          3.039           ms/op
Client.getUser:getUser·p0.90          sample          4.067           ms/op
Client.getUser:getUser·p0.95          sample          4.440           ms/op
Client.getUser:getUser·p0.99          sample         12.125           ms/op
Client.getUser:getUser·p0.999         sample         51.020           ms/op
Client.getUser:getUser·p0.9999        sample         53.805           ms/op
Client.getUser:getUser·p1.00          sample         53.805           ms/op
Client.listUser                       sample   3742   8.587 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          1.786           ms/op
Client.listUser:listUser·p0.50        sample          8.331           ms/op
Client.listUser:listUser·p0.90        sample         11.452           ms/op
Client.listUser:listUser·p0.95        sample         12.452           ms/op
Client.listUser:listUser·p0.99        sample         15.506           ms/op
Client.listUser:listUser·p0.999       sample         21.949           ms/op
Client.listUser:listUser·p0.9999      sample         22.905           ms/op
Client.listUser:listUser·p1.00        sample         22.905           ms/op
