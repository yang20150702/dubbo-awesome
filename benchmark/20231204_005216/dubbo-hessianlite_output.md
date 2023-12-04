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
# Warmup Iteration   1: 2.420 ops/ms
Iteration   1: 6.175 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.175 ops/ms


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
# Warmup Iteration   1: 5.143 ops/ms
Iteration   1: 12.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.491 ops/ms


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
# Warmup Iteration   1: 3.831 ops/ms
Iteration   1: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.189 ops/ms


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
# Warmup Iteration   1: 2.330 ops/ms
Iteration   1: 3.548 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.548 ops/ms


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
# Warmup Iteration   1: 5.976 ±(99.9%) 0.058 ms/op
Iteration   1: 3.353 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.353 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.048 ms/op
Iteration   1: 2.027 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.061 ms/op
Iteration   1: 3.168 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.168 ms/op


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
# Warmup Iteration   1: 12.984 ±(99.9%) 0.258 ms/op
Iteration   1: 8.616 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.616 ms/op


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.113 ms/op
Iteration   1: 2.948 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  12.911 ms/op
                 createUser·p0.9999: 12.943 ms/op
                 createUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11055
  mean =      2.948 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 2691 
    [ 2.500,  3.750) = 7491 
    [ 3.750,  5.000) = 519 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.072 ms/op
Iteration   1: 2.019 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.835 ms/op
                 existUser·p0.99:   3.659 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 6.835 ms/op
                 existUser·p1.00:   6.873 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15856
  mean =      2.019 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 7 
    [0.500, 1.000) = 172 
    [1.000, 1.500) = 1425 
    [1.500, 2.000) = 7179 
    [2.000, 2.500) = 4627 
    [2.500, 3.000) = 1968 
    [3.000, 3.500) = 266 
    [3.500, 4.000) = 103 
    [4.000, 4.500) = 57 
    [4.500, 5.000) = 13 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.835 ms/op
     p(99.0000) =      3.659 ms/op
     p(99.9000) =      5.751 ms/op
     p(99.9900) =      6.835 ms/op
     p(99.9990) =      6.873 ms/op
     p(99.9999) =      6.873 ms/op
    p(100.0000) =      6.873 ms/op


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.095 ms/op
Iteration   1: 2.648 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.281 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.262 ms/op
                 getUser·p0.999:  5.494 ms/op
                 getUser·p0.9999: 6.186 ms/op
                 getUser·p1.00:   6.234 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12167
  mean =      2.648 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 10 
    [1.000, 1.500) = 31 
    [1.500, 2.000) = 183 
    [2.000, 2.500) = 5275 
    [2.500, 3.000) = 4852 
    [3.000, 3.500) = 986 
    [3.500, 4.000) = 583 
    [4.000, 4.500) = 178 
    [4.500, 5.000) = 41 
    [5.000, 5.500) = 17 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.262 ms/op
     p(99.9000) =      5.494 ms/op
     p(99.9900) =      6.186 ms/op
     p(99.9990) =      6.234 ms/op
     p(99.9999) =      6.234 ms/op
    p(100.0000) =      6.234 ms/op


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
# Warmup Iteration   1: 13.758 ±(99.9%) 0.550 ms/op
Iteration   1: 8.335 ±(99.9%) 0.095 ms/op
                 listUser·p0.00:   3.428 ms/op
                 listUser·p0.50:   8.102 ms/op
                 listUser·p0.90:   10.604 ms/op
                 listUser·p0.95:   11.583 ms/op
                 listUser·p0.99:   13.930 ms/op
                 listUser·p0.999:  16.028 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3837
  mean =      8.335 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 3 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 966 
    [ 7.500,  8.750) = 1175 
    [ 8.750, 10.000) = 761 
    [10.000, 11.250) = 334 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.428 ms/op
     p(50.0000) =      8.102 ms/op
     p(90.0000) =     10.604 ms/op
     p(95.0000) =     11.583 ms/op
     p(99.0000) =     13.930 ms/op
     p(99.9000) =     16.028 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.175          ops/ms
Client.existUser                       thrpt         12.491          ops/ms
Client.getUser                         thrpt          8.189          ops/ms
Client.listUser                        thrpt          3.548          ops/ms
Client.createUser                       avgt          3.353           ms/op
Client.existUser                        avgt          2.027           ms/op
Client.getUser                          avgt          3.168           ms/op
Client.listUser                         avgt          8.616           ms/op
Client.createUser                     sample  11055   2.948 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.186           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.482           ms/op
Client.createUser:createUser·p0.95    sample          4.514           ms/op
Client.createUser:createUser·p0.99    sample          7.545           ms/op
Client.createUser:createUser·p0.999   sample         12.911           ms/op
Client.createUser:createUser·p0.9999  sample         12.943           ms/op
Client.createUser:createUser·p1.00    sample         12.943           ms/op
Client.existUser                      sample  15856   2.019 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.413           ms/op
Client.existUser:existUser·p0.50      sample          1.937           ms/op
Client.existUser:existUser·p0.90      sample          2.646           ms/op
Client.existUser:existUser·p0.95      sample          2.835           ms/op
Client.existUser:existUser·p0.99      sample          3.659           ms/op
Client.existUser:existUser·p0.999     sample          5.751           ms/op
Client.existUser:existUser·p0.9999    sample          6.835           ms/op
Client.existUser:existUser·p1.00      sample          6.873           ms/op
Client.getUser                        sample  12167   2.648 ± 0.014   ms/op
Client.getUser:getUser·p0.00          sample          0.730           ms/op
Client.getUser:getUser·p0.50          sample          2.527           ms/op
Client.getUser:getUser·p0.90          sample          3.281           ms/op
Client.getUser:getUser·p0.95          sample          3.621           ms/op
Client.getUser:getUser·p0.99          sample          4.262           ms/op
Client.getUser:getUser·p0.999         sample          5.494           ms/op
Client.getUser:getUser·p0.9999        sample          6.186           ms/op
Client.getUser:getUser·p1.00          sample          6.234           ms/op
Client.listUser                       sample   3837   8.335 ± 0.095   ms/op
Client.listUser:listUser·p0.00        sample          3.428           ms/op
Client.listUser:listUser·p0.50        sample          8.102           ms/op
Client.listUser:listUser·p0.90        sample         10.604           ms/op
Client.listUser:listUser·p0.95        sample         11.583           ms/op
Client.listUser:listUser·p0.99        sample         13.930           ms/op
Client.listUser:listUser·p0.999       sample         16.028           ms/op
Client.listUser:listUser·p0.9999      sample         17.662           ms/op
Client.listUser:listUser·p1.00        sample         17.662           ms/op
