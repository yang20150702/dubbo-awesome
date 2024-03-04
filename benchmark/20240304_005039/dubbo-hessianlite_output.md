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
# Warmup Iteration   1: 2.257 ops/ms
Iteration   1: 5.625 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.625 ops/ms


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
# Warmup Iteration   1: 5.436 ops/ms
Iteration   1: 11.900 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.900 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ops/ms
Iteration   1: 7.642 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.642 ops/ms


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
# Warmup Iteration   1: 2.056 ops/ms
Iteration   1: 3.631 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.631 ops/ms


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.067 ms/op
Iteration   1: 3.003 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.003 ms/op


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
# Warmup Iteration   1: 3.126 ±(99.9%) 0.063 ms/op
Iteration   1: 1.743 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.743 ms/op


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
# Warmup Iteration   1: 4.316 ±(99.9%) 0.047 ms/op
Iteration   1: 3.210 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.210 ms/op


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
# Warmup Iteration   1: 12.191 ±(99.9%) 0.314 ms/op
Iteration   1: 8.381 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.381 ms/op


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.108 ms/op
Iteration   1: 2.874 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.769 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.135 ms/op
                 createUser·p0.999:  6.920 ms/op
                 createUser·p0.9999: 9.055 ms/op
                 createUser·p1.00:   9.126 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11317
  mean =      2.874 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 11 
    [ 1.000,  2.000) = 250 
    [ 2.000,  3.000) = 7786 
    [ 3.000,  4.000) = 2689 
    [ 4.000,  5.000) = 450 
    [ 5.000,  6.000) = 90 
    [ 6.000,  7.000) = 33 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.769 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.135 ms/op
     p(99.9000) =      6.920 ms/op
     p(99.9900) =      9.055 ms/op
     p(99.9990) =      9.126 ms/op
     p(99.9999) =      9.126 ms/op
    p(100.0000) =      9.126 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.117 ms/op
Iteration   1: 1.908 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   3.208 ms/op
                 existUser·p0.999:  28.195 ms/op
                 existUser·p0.9999: 28.574 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16773
  mean =      1.908 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15377 
    [ 2.500,  5.000) = 1353 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.208 ms/op
     p(99.9000) =     28.195 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.102 ms/op
Iteration   1: 3.199 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  5.857 ms/op
                 getUser·p0.9999: 13.415 ms/op
                 getUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10006
  mean =      3.199 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 1056 
    [ 2.500,  3.750) = 7417 
    [ 3.750,  5.000) = 1390 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =      5.857 ms/op
     p(99.9900) =     13.415 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


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
# Warmup Iteration   1: 13.377 ±(99.9%) 0.424 ms/op
Iteration   1: 8.832 ±(99.9%) 0.117 ms/op
                 listUser·p0.00:   3.461 ms/op
                 listUser·p0.50:   8.585 ms/op
                 listUser·p0.90:   11.715 ms/op
                 listUser·p0.95:   12.599 ms/op
                 listUser·p0.99:   14.857 ms/op
                 listUser·p0.999:  20.428 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3621
  mean =      8.832 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 41 
    [ 5.000,  7.500) = 991 
    [ 7.500, 10.000) = 1668 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.461 ms/op
     p(50.0000) =      8.585 ms/op
     p(90.0000) =     11.715 ms/op
     p(95.0000) =     12.599 ms/op
     p(99.0000) =     14.857 ms/op
     p(99.9000) =     20.428 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.625          ops/ms
Client.existUser                       thrpt         11.900          ops/ms
Client.getUser                         thrpt          7.642          ops/ms
Client.listUser                        thrpt          3.631          ops/ms
Client.createUser                       avgt          3.003           ms/op
Client.existUser                        avgt          1.743           ms/op
Client.getUser                          avgt          3.210           ms/op
Client.listUser                         avgt          8.381           ms/op
Client.createUser                     sample  11317   2.874 ± 0.020   ms/op
Client.createUser:createUser·p0.00    sample          0.903           ms/op
Client.createUser:createUser·p0.50    sample          2.769           ms/op
Client.createUser:createUser·p0.90    sample          3.645           ms/op
Client.createUser:createUser·p0.95    sample          4.006           ms/op
Client.createUser:createUser·p0.99    sample          5.135           ms/op
Client.createUser:createUser·p0.999   sample          6.920           ms/op
Client.createUser:createUser·p0.9999  sample          9.055           ms/op
Client.createUser:createUser·p1.00    sample          9.126           ms/op
Client.existUser                      sample  16773   1.908 ± 0.032   ms/op
Client.existUser:existUser·p0.00      sample          0.461           ms/op
Client.existUser:existUser·p0.50      sample          1.835           ms/op
Client.existUser:existUser·p0.90      sample          2.437           ms/op
Client.existUser:existUser·p0.95      sample          2.679           ms/op
Client.existUser:existUser·p0.99      sample          3.208           ms/op
Client.existUser:existUser·p0.999     sample         28.195           ms/op
Client.existUser:existUser·p0.9999    sample         28.574           ms/op
Client.existUser:existUser·p1.00      sample         28.574           ms/op
Client.getUser                        sample  10006   3.199 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.699           ms/op
Client.getUser:getUser·p0.50          sample          3.174           ms/op
Client.getUser:getUser·p0.90          sample          3.969           ms/op
Client.getUser:getUser·p0.95          sample          4.284           ms/op
Client.getUser:getUser·p0.99          sample          5.218           ms/op
Client.getUser:getUser·p0.999         sample          5.857           ms/op
Client.getUser:getUser·p0.9999        sample         13.415           ms/op
Client.getUser:getUser·p1.00          sample         13.418           ms/op
Client.listUser                       sample   3621   8.832 ± 0.117   ms/op
Client.listUser:listUser·p0.00        sample          3.461           ms/op
Client.listUser:listUser·p0.50        sample          8.585           ms/op
Client.listUser:listUser·p0.90        sample         11.715           ms/op
Client.listUser:listUser·p0.95        sample         12.599           ms/op
Client.listUser:listUser·p0.99        sample         14.857           ms/op
Client.listUser:listUser·p0.999       sample         20.428           ms/op
Client.listUser:listUser·p0.9999      sample         23.495           ms/op
Client.listUser:listUser·p1.00        sample         23.495           ms/op
