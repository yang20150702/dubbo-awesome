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
# Warmup Iteration   1: 2.280 ops/ms
Iteration   1: 6.023 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.023 ops/ms


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
# Warmup Iteration   1: 6.303 ops/ms
Iteration   1: 12.683 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.683 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ops/ms
Iteration   1: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.301 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.987 ops/ms
Iteration   1: 3.448 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.448 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.308 ±(99.9%) 0.062 ms/op
Iteration   1: 3.081 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.081 ms/op


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
# Warmup Iteration   1: 2.997 ±(99.9%) 0.029 ms/op
Iteration   1: 2.027 ±(99.9%) 0.007 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.046 ms/op
Iteration   1: 3.120 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.120 ms/op


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
# Warmup Iteration   1: 15.441 ±(99.9%) 0.335 ms/op
Iteration   1: 9.436 ±(99.9%) 0.119 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.436 ms/op


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
# Warmup Iteration   1: 5.042 ±(99.9%) 0.103 ms/op
Iteration   1: 3.301 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.844 ms/op
                 createUser·p0.99:   11.145 ms/op
                 createUser·p0.999:  17.836 ms/op
                 createUser·p0.9999: 27.689 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9674
  mean =      3.301 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1683 
    [ 2.500,  5.000) = 7539 
    [ 5.000,  7.500) = 271 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.844 ms/op
     p(99.0000) =     11.145 ms/op
     p(99.9000) =     17.836 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.067 ms/op
Iteration   1: 1.988 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.482 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  19.071 ms/op
                 existUser·p0.9999: 19.580 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16081
  mean =      1.988 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 14388 
    [ 2.500,  3.750) = 1323 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     19.580 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.110 ms/op
Iteration   1: 3.102 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   7.052 ms/op
                 getUser·p0.999:  8.588 ms/op
                 getUser·p0.9999: 10.348 ms/op
                 getUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10423
  mean =      3.102 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 389 
    [ 2.000,  3.000) = 4620 
    [ 3.000,  4.000) = 4586 
    [ 4.000,  5.000) = 578 
    [ 5.000,  6.000) = 70 
    [ 6.000,  7.000) = 73 
    [ 7.000,  8.000) = 80 
    [ 8.000,  9.000) = 22 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      7.052 ms/op
     p(99.9000) =      8.588 ms/op
     p(99.9900) =     10.348 ms/op
     p(99.9990) =     10.355 ms/op
     p(99.9999) =     10.355 ms/op
    p(100.0000) =     10.355 ms/op


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
# Warmup Iteration   1: 12.515 ±(99.9%) 0.384 ms/op
Iteration   1: 8.882 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   8.634 ms/op
                 listUser·p0.90:   11.977 ms/op
                 listUser·p0.95:   12.829 ms/op
                 listUser·p0.99:   14.588 ms/op
                 listUser·p0.999:  18.906 ms/op
                 listUser·p0.9999: 35.521 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3630
  mean =      8.882 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 96 
    [ 5.000,  7.500) = 944 
    [ 7.500, 10.000) = 1589 
    [10.000, 12.500) = 764 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.470 ms/op
     p(50.0000) =      8.634 ms/op
     p(90.0000) =     11.977 ms/op
     p(95.0000) =     12.829 ms/op
     p(99.0000) =     14.588 ms/op
     p(99.9000) =     18.906 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     35.521 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.023          ops/ms
Client.existUser                       thrpt         12.683          ops/ms
Client.getUser                         thrpt          8.301          ops/ms
Client.listUser                        thrpt          3.448          ops/ms
Client.createUser                       avgt          3.081           ms/op
Client.existUser                        avgt          2.027           ms/op
Client.getUser                          avgt          3.120           ms/op
Client.listUser                         avgt          9.436           ms/op
Client.createUser                     sample   9674   3.301 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          0.813           ms/op
Client.createUser:createUser·p0.50    sample          3.068           ms/op
Client.createUser:createUser·p0.90    sample          3.899           ms/op
Client.createUser:createUser·p0.95    sample          4.844           ms/op
Client.createUser:createUser·p0.99    sample         11.145           ms/op
Client.createUser:createUser·p0.999   sample         17.836           ms/op
Client.createUser:createUser·p0.9999  sample         27.689           ms/op
Client.createUser:createUser·p1.00    sample         27.689           ms/op
Client.existUser                      sample  16081   1.988 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.615           ms/op
Client.existUser:existUser·p0.50      sample          1.870           ms/op
Client.existUser:existUser·p0.90      sample          2.482           ms/op
Client.existUser:existUser·p0.95      sample          2.699           ms/op
Client.existUser:existUser·p0.99      sample          4.153           ms/op
Client.existUser:existUser·p0.999     sample         19.071           ms/op
Client.existUser:existUser·p0.9999    sample         19.580           ms/op
Client.existUser:existUser·p1.00      sample         19.759           ms/op
Client.getUser                        sample  10423   3.102 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.104           ms/op
Client.getUser:getUser·p0.50          sample          3.023           ms/op
Client.getUser:getUser·p0.90          sample          3.924           ms/op
Client.getUser:getUser·p0.95          sample          4.194           ms/op
Client.getUser:getUser·p0.99          sample          7.052           ms/op
Client.getUser:getUser·p0.999         sample          8.588           ms/op
Client.getUser:getUser·p0.9999        sample         10.348           ms/op
Client.getUser:getUser·p1.00          sample         10.355           ms/op
Client.listUser                       sample   3630   8.882 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          2.470           ms/op
Client.listUser:listUser·p0.50        sample          8.634           ms/op
Client.listUser:listUser·p0.90        sample         11.977           ms/op
Client.listUser:listUser·p0.95        sample         12.829           ms/op
Client.listUser:listUser·p0.99        sample         14.588           ms/op
Client.listUser:listUser·p0.999       sample         18.906           ms/op
Client.listUser:listUser·p0.9999      sample         35.521           ms/op
Client.listUser:listUser·p1.00        sample         35.521           ms/op
