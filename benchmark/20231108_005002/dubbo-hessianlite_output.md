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
Iteration   1: 6.185 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.185 ops/ms


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
# Warmup Iteration   1: 6.640 ops/ms
Iteration   1: 13.364 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.364 ops/ms


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
# Warmup Iteration   1: 4.927 ops/ms
Iteration   1: 9.068 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.068 ops/ms


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
# Warmup Iteration   1: 2.029 ops/ms
Iteration   1: 3.825 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.825 ops/ms


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.070 ms/op
Iteration   1: 2.948 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.948 ms/op


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
# Warmup Iteration   1: 3.134 ±(99.9%) 0.035 ms/op
Iteration   1: 1.891 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.891 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.066 ms/op
Iteration   1: 2.577 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.577 ms/op


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
# Warmup Iteration   1: 12.346 ±(99.9%) 0.247 ms/op
Iteration   1: 8.699 ±(99.9%) 0.098 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.699 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.095 ms/op
Iteration   1: 3.281 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  20.054 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9752
  mean =      3.281 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1962 
    [ 2.500,  5.000) = 7437 
    [ 5.000,  7.500) = 236 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.058 ms/op
Iteration   1: 1.752 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.624 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.399 ms/op
                 existUser·p0.99:   3.065 ms/op
                 existUser·p0.999:  18.144 ms/op
                 existUser·p0.9999: 20.432 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18287
  mean =      1.752 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17647 
    [ 2.500,  5.000) = 527 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.399 ms/op
     p(99.0000) =      3.065 ms/op
     p(99.9000) =     18.144 ms/op
     p(99.9900) =     20.432 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.090 ms/op
Iteration   1: 2.916 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.863 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.020 ms/op
                 getUser·p0.99:   5.053 ms/op
                 getUser·p0.999:  7.007 ms/op
                 getUser·p0.9999: 12.664 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11071
  mean =      2.916 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3079 
    [ 2.500,  3.750) = 6781 
    [ 3.750,  5.000) = 1089 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.020 ms/op
     p(99.0000) =      5.053 ms/op
     p(99.9000) =      7.007 ms/op
     p(99.9900) =     12.664 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 10.813 ±(99.9%) 0.349 ms/op
Iteration   1: 7.538 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   7.127 ms/op
                 listUser·p0.90:   10.093 ms/op
                 listUser·p0.95:   11.108 ms/op
                 listUser·p0.99:   14.746 ms/op
                 listUser·p0.999:  24.243 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4234
  mean =      7.538 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 218 
    [ 5.000,  7.500) = 2310 
    [ 7.500, 10.000) = 1266 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      7.127 ms/op
     p(90.0000) =     10.093 ms/op
     p(95.0000) =     11.108 ms/op
     p(99.0000) =     14.746 ms/op
     p(99.9000) =     24.243 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.185          ops/ms
Client.existUser                       thrpt         13.364          ops/ms
Client.getUser                         thrpt          9.068          ops/ms
Client.listUser                        thrpt          3.825          ops/ms
Client.createUser                       avgt          2.948           ms/op
Client.existUser                        avgt          1.891           ms/op
Client.getUser                          avgt          2.577           ms/op
Client.listUser                         avgt          8.699           ms/op
Client.createUser                     sample   9752   3.281 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          0.666           ms/op
Client.createUser:createUser·p0.50    sample          3.125           ms/op
Client.createUser:createUser·p0.90    sample          4.137           ms/op
Client.createUser:createUser·p0.95    sample          4.481           ms/op
Client.createUser:createUser·p0.99    sample          8.331           ms/op
Client.createUser:createUser·p0.999   sample         20.054           ms/op
Client.createUser:createUser·p0.9999  sample         21.004           ms/op
Client.createUser:createUser·p1.00    sample         21.004           ms/op
Client.existUser                      sample  18287   1.752 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.524           ms/op
Client.existUser:existUser·p0.50      sample          1.624           ms/op
Client.existUser:existUser·p0.90      sample          2.138           ms/op
Client.existUser:existUser·p0.95      sample          2.399           ms/op
Client.existUser:existUser·p0.99      sample          3.065           ms/op
Client.existUser:existUser·p0.999     sample         18.144           ms/op
Client.existUser:existUser·p0.9999    sample         20.432           ms/op
Client.existUser:existUser·p1.00      sample         20.677           ms/op
Client.getUser                        sample  11071   2.916 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.812           ms/op
Client.getUser:getUser·p0.50          sample          2.863           ms/op
Client.getUser:getUser·p0.90          sample          3.777           ms/op
Client.getUser:getUser·p0.95          sample          4.020           ms/op
Client.getUser:getUser·p0.99          sample          5.053           ms/op
Client.getUser:getUser·p0.999         sample          7.007           ms/op
Client.getUser:getUser·p0.9999        sample         12.664           ms/op
Client.getUser:getUser·p1.00          sample         12.698           ms/op
Client.listUser                       sample   4234   7.538 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          1.841           ms/op
Client.listUser:listUser·p0.50        sample          7.127           ms/op
Client.listUser:listUser·p0.90        sample         10.093           ms/op
Client.listUser:listUser·p0.95        sample         11.108           ms/op
Client.listUser:listUser·p0.99        sample         14.746           ms/op
Client.listUser:listUser·p0.999       sample         24.243           ms/op
Client.listUser:listUser·p0.9999      sample         24.871           ms/op
Client.listUser:listUser·p1.00        sample         24.871           ms/op
