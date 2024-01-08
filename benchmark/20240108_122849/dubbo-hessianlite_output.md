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
# Warmup Iteration   1: 2.319 ops/ms
Iteration   1: 6.205 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.205 ops/ms


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
# Warmup Iteration   1: 6.316 ops/ms
Iteration   1: 14.083 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.083 ops/ms


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
# Warmup Iteration   1: 4.112 ops/ms
Iteration   1: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.381 ops/ms


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
# Warmup Iteration   1: 1.987 ops/ms
Iteration   1: 3.552 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.552 ops/ms


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.047 ms/op
Iteration   1: 3.222 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.222 ms/op


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
# Warmup Iteration   1: 3.607 ±(99.9%) 0.039 ms/op
Iteration   1: 1.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.908 ms/op


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
# Warmup Iteration   1: 4.752 ±(99.9%) 0.052 ms/op
Iteration   1: 2.788 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.788 ms/op


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
# Warmup Iteration   1: 12.344 ±(99.9%) 0.204 ms/op
Iteration   1: 8.959 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.959 ms/op


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
# Warmup Iteration   1: 5.488 ±(99.9%) 0.127 ms/op
Iteration   1: 3.355 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.772 ms/op
                 createUser·p0.99:   11.670 ms/op
                 createUser·p0.999:  19.296 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9569
  mean =      3.355 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1548 
    [ 2.500,  5.000) = 7633 
    [ 5.000,  7.500) = 200 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.772 ms/op
     p(99.0000) =     11.670 ms/op
     p(99.9000) =     19.296 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 2.980 ±(99.9%) 0.063 ms/op
Iteration   1: 1.949 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.413 ms/op
                 existUser·p0.999:  16.597 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16638
  mean =      1.949 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15643 
    [ 2.500,  5.000) = 891 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.413 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.096 ms/op
Iteration   1: 3.005 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   2.843 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  7.564 ms/op
                 getUser·p0.9999: 8.052 ms/op
                 getUser·p1.00:   8.077 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10641
  mean =      3.005 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 415 
    [2.000, 2.500) = 2321 
    [2.500, 3.000) = 3295 
    [3.000, 3.500) = 2135 
    [3.500, 4.000) = 1570 
    [4.000, 4.500) = 577 
    [4.500, 5.000) = 186 
    [5.000, 5.500) = 73 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 12 
    [7.500, 8.000) = 19 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      7.564 ms/op
     p(99.9900) =      8.052 ms/op
     p(99.9990) =      8.077 ms/op
     p(99.9999) =      8.077 ms/op
    p(100.0000) =      8.077 ms/op


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
# Warmup Iteration   1: 13.047 ±(99.9%) 0.483 ms/op
Iteration   1: 7.989 ±(99.9%) 0.146 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   7.578 ms/op
                 listUser·p0.90:   10.188 ms/op
                 listUser·p0.95:   11.148 ms/op
                 listUser·p0.99:   17.197 ms/op
                 listUser·p0.999:  39.916 ms/op
                 listUser·p0.9999: 48.169 ms/op
                 listUser·p1.00:   48.169 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4011
  mean =      7.989 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 115 
    [ 5.000, 10.000) = 3447 
    [10.000, 15.000) = 405 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      7.578 ms/op
     p(90.0000) =     10.188 ms/op
     p(95.0000) =     11.148 ms/op
     p(99.0000) =     17.197 ms/op
     p(99.9000) =     39.916 ms/op
     p(99.9900) =     48.169 ms/op
     p(99.9990) =     48.169 ms/op
     p(99.9999) =     48.169 ms/op
    p(100.0000) =     48.169 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.205          ops/ms
Client.existUser                       thrpt         14.083          ops/ms
Client.getUser                         thrpt          8.381          ops/ms
Client.listUser                        thrpt          3.552          ops/ms
Client.createUser                       avgt          3.222           ms/op
Client.existUser                        avgt          1.908           ms/op
Client.getUser                          avgt          2.788           ms/op
Client.listUser                         avgt          8.959           ms/op
Client.createUser                     sample   9569   3.355 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          1.126           ms/op
Client.createUser:createUser·p0.50    sample          3.080           ms/op
Client.createUser:createUser·p0.90    sample          4.375           ms/op
Client.createUser:createUser·p0.95    sample          4.772           ms/op
Client.createUser:createUser·p0.99    sample         11.670           ms/op
Client.createUser:createUser·p0.999   sample         19.296           ms/op
Client.createUser:createUser·p0.9999  sample         21.594           ms/op
Client.createUser:createUser·p1.00    sample         21.594           ms/op
Client.existUser                      sample  16638   1.949 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.792           ms/op
Client.existUser:existUser·p0.50      sample          1.880           ms/op
Client.existUser:existUser·p0.90      sample          2.363           ms/op
Client.existUser:existUser·p0.95      sample          2.576           ms/op
Client.existUser:existUser·p0.99      sample          3.413           ms/op
Client.existUser:existUser·p0.999     sample         16.597           ms/op
Client.existUser:existUser·p0.9999    sample         21.791           ms/op
Client.existUser:existUser·p1.00      sample         21.791           ms/op
Client.getUser                        sample  10641   3.005 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.081           ms/op
Client.getUser:getUser·p0.50          sample          2.843           ms/op
Client.getUser:getUser·p0.90          sample          3.928           ms/op
Client.getUser:getUser·p0.95          sample          4.235           ms/op
Client.getUser:getUser·p0.99          sample          5.202           ms/op
Client.getUser:getUser·p0.999         sample          7.564           ms/op
Client.getUser:getUser·p0.9999        sample          8.052           ms/op
Client.getUser:getUser·p1.00          sample          8.077           ms/op
Client.listUser                       sample   4011   7.989 ± 0.146   ms/op
Client.listUser:listUser·p0.00        sample          2.146           ms/op
Client.listUser:listUser·p0.50        sample          7.578           ms/op
Client.listUser:listUser·p0.90        sample         10.188           ms/op
Client.listUser:listUser·p0.95        sample         11.148           ms/op
Client.listUser:listUser·p0.99        sample         17.197           ms/op
Client.listUser:listUser·p0.999       sample         39.916           ms/op
Client.listUser:listUser·p0.9999      sample         48.169           ms/op
Client.listUser:listUser·p1.00        sample         48.169           ms/op
