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
# Warmup Iteration   1: 1.982 ops/ms
Iteration   1: 5.777 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.777 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ops/ms
Iteration   1: 13.245 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.245 ops/ms


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
# Warmup Iteration   1: 4.396 ops/ms
Iteration   1: 8.996 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.996 ops/ms


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
# Warmup Iteration   1: 2.165 ops/ms
Iteration   1: 3.173 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.173 ops/ms


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.074 ms/op
Iteration   1: 3.133 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.133 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.043 ms/op
Iteration   1: 2.116 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.116 ms/op


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
# Warmup Iteration   1: 5.481 ±(99.9%) 0.083 ms/op
Iteration   1: 3.218 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.218 ms/op


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
# Warmup Iteration   1: 12.817 ±(99.9%) 0.238 ms/op
Iteration   1: 9.111 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.111 ms/op


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
# Warmup Iteration   1: 5.172 ±(99.9%) 0.110 ms/op
Iteration   1: 3.158 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  11.764 ms/op
                 createUser·p0.9999: 11.813 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10235
  mean =      3.158 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1444 
    [ 2.500,  3.750) = 7021 
    [ 3.750,  5.000) = 1672 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.079 ms/op
Iteration   1: 1.972 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.469 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.439 ms/op
                 existUser·p0.999:  24.799 ms/op
                 existUser·p0.9999: 25.556 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16207
  mean =      1.972 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15027 
    [ 2.500,  5.000) = 1095 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.439 ms/op
     p(99.9000) =     24.799 ms/op
     p(99.9900) =     25.556 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.090 ms/op
Iteration   1: 3.047 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 10.447 ms/op
                 getUser·p1.00:   10.469 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10496
  mean =      3.047 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 526 
    [ 2.000,  3.000) = 5019 
    [ 3.000,  4.000) = 3846 
    [ 4.000,  5.000) = 876 
    [ 5.000,  6.000) = 185 
    [ 6.000,  7.000) = 22 
    [ 7.000,  8.000) = 7 
    [ 8.000,  9.000) = 5 
    [ 9.000, 10.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     10.447 ms/op
     p(99.9990) =     10.469 ms/op
     p(99.9999) =     10.469 ms/op
    p(100.0000) =     10.469 ms/op


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
# Warmup Iteration   1: 12.231 ±(99.9%) 0.355 ms/op
Iteration   1: 8.588 ±(99.9%) 0.117 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   8.266 ms/op
                 listUser·p0.90:   11.387 ms/op
                 listUser·p0.95:   12.567 ms/op
                 listUser·p0.99:   14.350 ms/op
                 listUser·p0.999:  19.413 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3714
  mean =      8.588 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 63 
    [ 5.000,  7.500) = 1201 
    [ 7.500, 10.000) = 1548 
    [10.000, 12.500) = 711 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.494 ms/op
     p(50.0000) =      8.266 ms/op
     p(90.0000) =     11.387 ms/op
     p(95.0000) =     12.567 ms/op
     p(99.0000) =     14.350 ms/op
     p(99.9000) =     19.413 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.777          ops/ms
Client.existUser                       thrpt         13.245          ops/ms
Client.getUser                         thrpt          8.996          ops/ms
Client.listUser                        thrpt          3.173          ops/ms
Client.createUser                       avgt          3.133           ms/op
Client.existUser                        avgt          2.116           ms/op
Client.getUser                          avgt          3.218           ms/op
Client.listUser                         avgt          9.111           ms/op
Client.createUser                     sample  10235   3.158 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.155           ms/op
Client.createUser:createUser·p0.50    sample          3.092           ms/op
Client.createUser:createUser·p0.90    sample          3.899           ms/op
Client.createUser:createUser·p0.95    sample          4.100           ms/op
Client.createUser:createUser·p0.99    sample          4.874           ms/op
Client.createUser:createUser·p0.999   sample         11.764           ms/op
Client.createUser:createUser·p0.9999  sample         11.813           ms/op
Client.createUser:createUser·p1.00    sample         11.813           ms/op
Client.existUser                      sample  16207   1.972 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample          0.469           ms/op
Client.existUser:existUser·p0.50      sample          1.827           ms/op
Client.existUser:existUser·p0.90      sample          2.413           ms/op
Client.existUser:existUser·p0.95      sample          2.630           ms/op
Client.existUser:existUser·p0.99      sample          3.439           ms/op
Client.existUser:existUser·p0.999     sample         24.799           ms/op
Client.existUser:existUser·p0.9999    sample         25.556           ms/op
Client.existUser:existUser·p1.00      sample         25.657           ms/op
Client.getUser                        sample  10496   3.047 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.774           ms/op
Client.getUser:getUser·p0.50          sample          2.937           ms/op
Client.getUser:getUser·p0.90          sample          4.039           ms/op
Client.getUser:getUser·p0.95          sample          4.432           ms/op
Client.getUser:getUser·p0.99          sample          5.448           ms/op
Client.getUser:getUser·p0.999         sample          8.520           ms/op
Client.getUser:getUser·p0.9999        sample         10.447           ms/op
Client.getUser:getUser·p1.00          sample         10.469           ms/op
Client.listUser                       sample   3714   8.588 ± 0.117   ms/op
Client.listUser:listUser·p0.00        sample          2.494           ms/op
Client.listUser:listUser·p0.50        sample          8.266           ms/op
Client.listUser:listUser·p0.90        sample         11.387           ms/op
Client.listUser:listUser·p0.95        sample         12.567           ms/op
Client.listUser:listUser·p0.99        sample         14.350           ms/op
Client.listUser:listUser·p0.999       sample         19.413           ms/op
Client.listUser:listUser·p0.9999      sample         22.249           ms/op
Client.listUser:listUser·p1.00        sample         22.249           ms/op
