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
# Warmup Iteration   1: 2.510 ops/ms
Iteration   1: 5.915 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.915 ops/ms


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
# Warmup Iteration   1: 5.266 ops/ms
Iteration   1: 11.777 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.777 ops/ms


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
# Warmup Iteration   1: 3.635 ops/ms
Iteration   1: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.910 ops/ms


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
# Warmup Iteration   1: 2.086 ops/ms
Iteration   1: 3.607 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.607 ops/ms


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
# Warmup Iteration   1: 5.578 ±(99.9%) 0.058 ms/op
Iteration   1: 3.043 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.043 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.066 ms/op
Iteration   1: 2.028 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.028 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.056 ms/op
Iteration   1: 3.341 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.341 ms/op


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
# Warmup Iteration   1: 12.255 ±(99.9%) 0.241 ms/op
Iteration   1: 8.657 ±(99.9%) 0.122 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.657 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.108 ms/op
Iteration   1: 3.100 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.839 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   7.878 ms/op
                 createUser·p0.999:  12.638 ms/op
                 createUser·p0.9999: 13.054 ms/op
                 createUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10327
  mean =      3.100 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2186 
    [ 2.500,  3.750) = 6811 
    [ 3.750,  5.000) = 1119 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.839 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      7.878 ms/op
     p(99.9000) =     12.638 ms/op
     p(99.9900) =     13.054 ms/op
     p(99.9990) =     13.058 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.099 ms/op
Iteration   1: 1.916 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   4.873 ms/op
                 existUser·p0.999:  19.071 ms/op
                 existUser·p0.9999: 19.353 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17015
  mean =      1.916 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 15434 
    [ 2.500,  3.750) = 975 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      4.873 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     19.353 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.111 ms/op
Iteration   1: 3.371 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.777 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 9.683 ms/op
                 getUser·p1.00:   9.683 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9497
  mean =      3.371 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 101 
    [ 2.000,  3.000) = 3349 
    [ 3.000,  4.000) = 4344 
    [ 4.000,  5.000) = 1340 
    [ 5.000,  6.000) = 282 
    [ 6.000,  7.000) = 13 
    [ 7.000,  8.000) = 34 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.777 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =      9.683 ms/op
     p(99.9990) =      9.683 ms/op
     p(99.9999) =      9.683 ms/op
    p(100.0000) =      9.683 ms/op


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
# Warmup Iteration   1: 12.329 ±(99.9%) 0.395 ms/op
Iteration   1: 8.067 ±(99.9%) 0.100 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   7.840 ms/op
                 listUser·p0.90:   10.142 ms/op
                 listUser·p0.95:   11.239 ms/op
                 listUser·p0.99:   14.487 ms/op
                 listUser·p0.999:  20.736 ms/op
                 listUser·p0.9999: 27.558 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4091
  mean =      8.067 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 106 
    [ 5.000,  7.500) = 1588 
    [ 7.500, 10.000) = 1936 
    [10.000, 12.500) = 373 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.744 ms/op
     p(50.0000) =      7.840 ms/op
     p(90.0000) =     10.142 ms/op
     p(95.0000) =     11.239 ms/op
     p(99.0000) =     14.487 ms/op
     p(99.9000) =     20.736 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.915          ops/ms
Client.existUser                       thrpt         11.777          ops/ms
Client.getUser                         thrpt          7.910          ops/ms
Client.listUser                        thrpt          3.607          ops/ms
Client.createUser                       avgt          3.043           ms/op
Client.existUser                        avgt          2.028           ms/op
Client.getUser                          avgt          3.341           ms/op
Client.listUser                         avgt          8.657           ms/op
Client.createUser                     sample  10327   3.100 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.208           ms/op
Client.createUser:createUser·p0.50    sample          2.912           ms/op
Client.createUser:createUser·p0.90    sample          3.839           ms/op
Client.createUser:createUser·p0.95    sample          4.162           ms/op
Client.createUser:createUser·p0.99    sample          7.878           ms/op
Client.createUser:createUser·p0.999   sample         12.638           ms/op
Client.createUser:createUser·p0.9999  sample         13.054           ms/op
Client.createUser:createUser·p1.00    sample         13.058           ms/op
Client.existUser                      sample  17015   1.916 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.600           ms/op
Client.existUser:existUser·p0.50      sample          1.757           ms/op
Client.existUser:existUser·p0.90      sample          2.392           ms/op
Client.existUser:existUser·p0.95      sample          2.605           ms/op
Client.existUser:existUser·p0.99      sample          4.873           ms/op
Client.existUser:existUser·p0.999     sample         19.071           ms/op
Client.existUser:existUser·p0.9999    sample         19.353           ms/op
Client.existUser:existUser·p1.00      sample         19.399           ms/op
Client.getUser                        sample   9497   3.371 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.521           ms/op
Client.getUser:getUser·p0.50          sample          3.277           ms/op
Client.getUser:getUser·p0.90          sample          4.309           ms/op
Client.getUser:getUser·p0.95          sample          4.777           ms/op
Client.getUser:getUser·p0.99          sample          5.751           ms/op
Client.getUser:getUser·p0.999         sample          9.470           ms/op
Client.getUser:getUser·p0.9999        sample          9.683           ms/op
Client.getUser:getUser·p1.00          sample          9.683           ms/op
Client.listUser                       sample   4091   8.067 ± 0.100   ms/op
Client.listUser:listUser·p0.00        sample          2.744           ms/op
Client.listUser:listUser·p0.50        sample          7.840           ms/op
Client.listUser:listUser·p0.90        sample         10.142           ms/op
Client.listUser:listUser·p0.95        sample         11.239           ms/op
Client.listUser:listUser·p0.99        sample         14.487           ms/op
Client.listUser:listUser·p0.999       sample         20.736           ms/op
Client.listUser:listUser·p0.9999      sample         27.558           ms/op
Client.listUser:listUser·p1.00        sample         27.558           ms/op
