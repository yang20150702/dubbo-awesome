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
# Warmup Iteration   1: 2.954 ops/ms
Iteration   1: 5.990 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.990 ops/ms


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
# Warmup Iteration   1: 6.333 ops/ms
Iteration   1: 14.028 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.028 ops/ms


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
# Warmup Iteration   1: 4.345 ops/ms
Iteration   1: 9.559 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.559 ops/ms


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
# Warmup Iteration   1: 2.477 ops/ms
Iteration   1: 3.829 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.829 ops/ms


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
# Warmup Iteration   1: 5.462 ±(99.9%) 0.066 ms/op
Iteration   1: 3.147 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.147 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.029 ms/op
Iteration   1: 1.818 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.059 ms/op
Iteration   1: 2.807 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.807 ms/op


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
# Warmup Iteration   1: 11.120 ±(99.9%) 0.158 ms/op
Iteration   1: 7.304 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.304 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.098 ms/op
Iteration   1: 3.222 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.049 ms/op
                 createUser·p0.99:   12.791 ms/op
                 createUser·p0.999:  27.197 ms/op
                 createUser·p0.9999: 27.296 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9928
  mean =      3.222 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 988 
    [ 2.500,  5.000) = 8641 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.049 ms/op
     p(99.0000) =     12.791 ms/op
     p(99.9000) =     27.197 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 2.979 ±(99.9%) 0.060 ms/op
Iteration   1: 1.826 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   3.372 ms/op
                 existUser·p0.999:  16.970 ms/op
                 existUser·p0.9999: 17.424 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17519
  mean =      1.826 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 683 
    [ 1.250,  2.500) = 15874 
    [ 2.500,  3.750) = 817 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.372 ms/op
     p(99.9000) =     16.970 ms/op
     p(99.9900) =     17.424 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.116 ms/op
Iteration   1: 2.904 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   2.802 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  12.695 ms/op
                 getUser·p0.9999: 13.214 ms/op
                 getUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11132
  mean =      2.904 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3634 
    [ 2.500,  3.750) = 6508 
    [ 3.750,  5.000) = 772 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     12.695 ms/op
     p(99.9900) =     13.214 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 10.528 ±(99.9%) 0.320 ms/op
Iteration   1: 8.047 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   2.900 ms/op
                 listUser·p0.50:   7.528 ms/op
                 listUser·p0.90:   10.650 ms/op
                 listUser·p0.95:   11.878 ms/op
                 listUser·p0.99:   18.612 ms/op
                 listUser·p0.999:  24.576 ms/op
                 listUser·p0.9999: 27.853 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3999
  mean =      8.047 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 1868 
    [ 7.500, 10.000) = 1443 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.900 ms/op
     p(50.0000) =      7.528 ms/op
     p(90.0000) =     10.650 ms/op
     p(95.0000) =     11.878 ms/op
     p(99.0000) =     18.612 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.990          ops/ms
Client.existUser                       thrpt         14.028          ops/ms
Client.getUser                         thrpt          9.559          ops/ms
Client.listUser                        thrpt          3.829          ops/ms
Client.createUser                       avgt          3.147           ms/op
Client.existUser                        avgt          1.818           ms/op
Client.getUser                          avgt          2.807           ms/op
Client.listUser                         avgt          7.304           ms/op
Client.createUser                     sample   9928   3.222 ± 0.061   ms/op
Client.createUser:createUser·p0.00    sample          1.051           ms/op
Client.createUser:createUser·p0.50    sample          2.949           ms/op
Client.createUser:createUser·p0.90    sample          3.604           ms/op
Client.createUser:createUser·p0.95    sample          4.049           ms/op
Client.createUser:createUser·p0.99    sample         12.791           ms/op
Client.createUser:createUser·p0.999   sample         27.197           ms/op
Client.createUser:createUser·p0.9999  sample         27.296           ms/op
Client.createUser:createUser·p1.00    sample         27.296           ms/op
Client.existUser                      sample  17519   1.826 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.582           ms/op
Client.existUser:existUser·p0.50      sample          1.737           ms/op
Client.existUser:existUser·p0.90      sample          2.302           ms/op
Client.existUser:existUser·p0.95      sample          2.535           ms/op
Client.existUser:existUser·p0.99      sample          3.372           ms/op
Client.existUser:existUser·p0.999     sample         16.970           ms/op
Client.existUser:existUser·p0.9999    sample         17.424           ms/op
Client.existUser:existUser·p1.00      sample         17.695           ms/op
Client.getUser                        sample  11132   2.904 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.276           ms/op
Client.getUser:getUser·p0.50          sample          2.802           ms/op
Client.getUser:getUser·p0.90          sample          3.690           ms/op
Client.getUser:getUser·p0.95          sample          4.039           ms/op
Client.getUser:getUser·p0.99          sample          5.833           ms/op
Client.getUser:getUser·p0.999         sample         12.695           ms/op
Client.getUser:getUser·p0.9999        sample         13.214           ms/op
Client.getUser:getUser·p1.00          sample         13.222           ms/op
Client.listUser                       sample   3999   8.047 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          2.900           ms/op
Client.listUser:listUser·p0.50        sample          7.528           ms/op
Client.listUser:listUser·p0.90        sample         10.650           ms/op
Client.listUser:listUser·p0.95        sample         11.878           ms/op
Client.listUser:listUser·p0.99        sample         18.612           ms/op
Client.listUser:listUser·p0.999       sample         24.576           ms/op
Client.listUser:listUser·p0.9999      sample         27.853           ms/op
Client.listUser:listUser·p1.00        sample         27.853           ms/op
