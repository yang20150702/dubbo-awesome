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
# Warmup Iteration   1: 2.259 ops/ms
Iteration   1: 5.937 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.937 ops/ms


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
# Warmup Iteration   1: 6.289 ops/ms
Iteration   1: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.707 ops/ms


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
# Warmup Iteration   1: 4.442 ops/ms
Iteration   1: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.941 ops/ms


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
# Warmup Iteration   1: 2.423 ops/ms
Iteration   1: 3.840 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.840 ops/ms


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.086 ms/op
Iteration   1: 3.116 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.116 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.062 ms/op
Iteration   1: 2.007 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.007 ms/op


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.086 ms/op
Iteration   1: 3.078 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.078 ms/op


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
# Warmup Iteration   1: 11.644 ±(99.9%) 0.188 ms/op
Iteration   1: 9.380 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.380 ms/op


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.130 ms/op
Iteration   1: 3.111 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.753 ms/op
                 createUser·p0.90:   4.181 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   10.361 ms/op
                 createUser·p0.999:  17.027 ms/op
                 createUser·p0.9999: 18.690 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10362
  mean =      3.111 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 3111 
    [ 2.500,  3.750) = 5477 
    [ 3.750,  5.000) = 1207 
    [ 5.000,  6.250) = 212 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      4.181 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =     10.361 ms/op
     p(99.9000) =     17.027 ms/op
     p(99.9900) =     18.690 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 2.821 ±(99.9%) 0.056 ms/op
Iteration   1: 1.906 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   2.905 ms/op
                 existUser·p0.999:  20.218 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16777
  mean =      1.906 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16295 
    [ 2.500,  5.000) = 417 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      2.905 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.121 ms/op
Iteration   1: 3.027 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.548 ms/op
                 getUser·p0.999:  13.615 ms/op
                 getUser·p0.9999: 13.745 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10567
  mean =      3.027 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 2593 
    [ 2.500,  3.750) = 6861 
    [ 3.750,  5.000) = 798 
    [ 5.000,  6.250) = 156 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.548 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     13.745 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 10.875 ±(99.9%) 0.315 ms/op
Iteration   1: 7.203 ±(99.9%) 0.085 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   6.980 ms/op
                 listUser·p0.90:   9.110 ms/op
                 listUser·p0.95:   9.978 ms/op
                 listUser·p0.99:   13.077 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4441
  mean =      7.203 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3 
    [ 2.500,  3.750) = 26 
    [ 3.750,  5.000) = 215 
    [ 5.000,  6.250) = 979 
    [ 6.250,  7.500) = 1633 
    [ 7.500,  8.750) = 979 
    [ 8.750, 10.000) = 385 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      6.980 ms/op
     p(90.0000) =      9.110 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     13.077 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.937          ops/ms
Client.existUser                       thrpt         12.707          ops/ms
Client.getUser                         thrpt          7.941          ops/ms
Client.listUser                        thrpt          3.840          ops/ms
Client.createUser                       avgt          3.116           ms/op
Client.existUser                        avgt          2.007           ms/op
Client.getUser                          avgt          3.078           ms/op
Client.listUser                         avgt          9.380           ms/op
Client.createUser                     sample  10362   3.111 ± 0.050   ms/op
Client.createUser:createUser·p0.00    sample          0.955           ms/op
Client.createUser:createUser·p0.50    sample          2.753           ms/op
Client.createUser:createUser·p0.90    sample          4.181           ms/op
Client.createUser:createUser·p0.95    sample          5.005           ms/op
Client.createUser:createUser·p0.99    sample         10.361           ms/op
Client.createUser:createUser·p0.999   sample         17.027           ms/op
Client.createUser:createUser·p0.9999  sample         18.690           ms/op
Client.createUser:createUser·p1.00    sample         18.711           ms/op
Client.existUser                      sample  16777   1.906 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.584           ms/op
Client.existUser:existUser·p0.50      sample          1.851           ms/op
Client.existUser:existUser·p0.90      sample          2.265           ms/op
Client.existUser:existUser·p0.95      sample          2.380           ms/op
Client.existUser:existUser·p0.99      sample          2.905           ms/op
Client.existUser:existUser·p0.999     sample         20.218           ms/op
Client.existUser:existUser·p0.9999    sample         20.939           ms/op
Client.existUser:existUser·p1.00      sample         20.939           ms/op
Client.getUser                        sample  10567   3.027 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.797           ms/op
Client.getUser:getUser·p0.50          sample          2.998           ms/op
Client.getUser:getUser·p0.90          sample          3.760           ms/op
Client.getUser:getUser·p0.95          sample          4.194           ms/op
Client.getUser:getUser·p0.99          sample          6.548           ms/op
Client.getUser:getUser·p0.999         sample         13.615           ms/op
Client.getUser:getUser·p0.9999        sample         13.745           ms/op
Client.getUser:getUser·p1.00          sample         13.746           ms/op
Client.listUser                       sample   4441   7.203 ± 0.085   ms/op
Client.listUser:listUser·p0.00        sample          1.874           ms/op
Client.listUser:listUser·p0.50        sample          6.980           ms/op
Client.listUser:listUser·p0.90        sample          9.110           ms/op
Client.listUser:listUser·p0.95        sample          9.978           ms/op
Client.listUser:listUser·p0.99        sample         13.077           ms/op
Client.listUser:listUser·p0.999       sample         18.940           ms/op
Client.listUser:listUser·p0.9999      sample         19.399           ms/op
Client.listUser:listUser·p1.00        sample         19.399           ms/op
