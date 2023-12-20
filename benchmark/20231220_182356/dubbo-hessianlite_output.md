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
# Warmup Iteration   1: 2.395 ops/ms
Iteration   1: 6.488 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.488 ops/ms


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
# Warmup Iteration   1: 5.446 ops/ms
Iteration   1: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.779 ops/ms


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
# Warmup Iteration   1: 4.458 ops/ms
Iteration   1: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.140 ops/ms


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
# Warmup Iteration   1: 2.130 ops/ms
Iteration   1: 4.385 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.385 ops/ms


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
# Warmup Iteration   1: 5.379 ±(99.9%) 0.064 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.223 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.050 ms/op
Iteration   1: 1.941 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.941 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.046 ms/op
Iteration   1: 2.891 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.891 ms/op


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
# Warmup Iteration   1: 11.669 ±(99.9%) 0.204 ms/op
Iteration   1: 8.341 ±(99.9%) 0.104 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.341 ms/op


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
# Warmup Iteration   1: 4.992 ±(99.9%) 0.119 ms/op
Iteration   1: 2.986 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.296 ms/op
                 createUser·p0.99:   7.201 ms/op
                 createUser·p0.999:  17.279 ms/op
                 createUser·p0.9999: 19.268 ms/op
                 createUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10691
  mean =      2.986 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 3503 
    [ 2.500,  3.750) = 6211 
    [ 3.750,  5.000) = 667 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.296 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     17.279 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.065 ms/op
Iteration   1: 2.007 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.399 ms/op
                 existUser·p0.50:   1.972 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  8.143 ms/op
                 existUser·p0.9999: 8.765 ms/op
                 existUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15934
  mean =      2.007 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 6 
    [0.500, 1.000) = 193 
    [1.000, 1.500) = 2029 
    [1.500, 2.000) = 5988 
    [2.000, 2.500) = 5206 
    [2.500, 3.000) = 2142 
    [3.000, 3.500) = 285 
    [3.500, 4.000) = 18 
    [4.000, 4.500) = 11 
    [4.500, 5.000) = 19 
    [5.000, 5.500) = 4 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =      8.765 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.111 ms/op
Iteration   1: 2.914 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.261 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 8.054 ms/op
                 getUser·p1.00:   8.061 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10978
  mean =      2.914 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 58 
    [1.500, 2.000) = 843 
    [2.000, 2.500) = 2318 
    [2.500, 3.000) = 2692 
    [3.000, 3.500) = 3378 
    [3.500, 4.000) = 1168 
    [4.000, 4.500) = 256 
    [4.500, 5.000) = 128 
    [5.000, 5.500) = 72 
    [5.500, 6.000) = 24 
    [6.000, 6.500) = 24 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.261 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =      8.054 ms/op
     p(99.9990) =      8.061 ms/op
     p(99.9999) =      8.061 ms/op
    p(100.0000) =      8.061 ms/op


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
# Warmup Iteration   1: 12.046 ±(99.9%) 0.448 ms/op
Iteration   1: 7.932 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   7.668 ms/op
                 listUser·p0.90:   10.355 ms/op
                 listUser·p0.95:   11.387 ms/op
                 listUser·p0.99:   18.199 ms/op
                 listUser·p0.999:  21.221 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4019
  mean =      7.932 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 213 
    [ 5.000,  7.500) = 1638 
    [ 7.500, 10.000) = 1658 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.773 ms/op
     p(50.0000) =      7.668 ms/op
     p(90.0000) =     10.355 ms/op
     p(95.0000) =     11.387 ms/op
     p(99.0000) =     18.199 ms/op
     p(99.9000) =     21.221 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.488          ops/ms
Client.existUser                       thrpt         12.779          ops/ms
Client.getUser                         thrpt          9.140          ops/ms
Client.listUser                        thrpt          4.385          ops/ms
Client.createUser                       avgt          3.223           ms/op
Client.existUser                        avgt          1.941           ms/op
Client.getUser                          avgt          2.891           ms/op
Client.listUser                         avgt          8.341           ms/op
Client.createUser                     sample  10691   2.986 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          0.858           ms/op
Client.createUser:createUser·p0.50    sample          2.814           ms/op
Client.createUser:createUser·p0.90    sample          3.662           ms/op
Client.createUser:createUser·p0.95    sample          4.296           ms/op
Client.createUser:createUser·p0.99    sample          7.201           ms/op
Client.createUser:createUser·p0.999   sample         17.279           ms/op
Client.createUser:createUser·p0.9999  sample         19.268           ms/op
Client.createUser:createUser·p1.00    sample         19.268           ms/op
Client.existUser                      sample  15934   2.007 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.399           ms/op
Client.existUser:existUser·p0.50      sample          1.972           ms/op
Client.existUser:existUser·p0.90      sample          2.621           ms/op
Client.existUser:existUser·p0.95      sample          2.781           ms/op
Client.existUser:existUser·p0.99      sample          3.277           ms/op
Client.existUser:existUser·p0.999     sample          8.143           ms/op
Client.existUser:existUser·p0.9999    sample          8.765           ms/op
Client.existUser:existUser·p1.00      sample          8.765           ms/op
Client.getUser                        sample  10978   2.914 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.041           ms/op
Client.getUser:getUser·p0.50          sample          2.925           ms/op
Client.getUser:getUser·p0.90          sample          3.670           ms/op
Client.getUser:getUser·p0.95          sample          3.957           ms/op
Client.getUser:getUser·p0.99          sample          5.261           ms/op
Client.getUser:getUser·p0.999         sample          6.750           ms/op
Client.getUser:getUser·p0.9999        sample          8.054           ms/op
Client.getUser:getUser·p1.00          sample          8.061           ms/op
Client.listUser                       sample   4019   7.932 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          2.773           ms/op
Client.listUser:listUser·p0.50        sample          7.668           ms/op
Client.listUser:listUser·p0.90        sample         10.355           ms/op
Client.listUser:listUser·p0.95        sample         11.387           ms/op
Client.listUser:listUser·p0.99        sample         18.199           ms/op
Client.listUser:listUser·p0.999       sample         21.221           ms/op
Client.listUser:listUser·p0.9999      sample         25.821           ms/op
Client.listUser:listUser·p1.00        sample         25.821           ms/op
