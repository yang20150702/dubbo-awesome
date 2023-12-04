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
# Warmup Iteration   1: 2.522 ops/ms
Iteration   1: 5.973 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.973 ops/ms


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
# Warmup Iteration   1: 5.835 ops/ms
Iteration   1: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.894 ops/ms


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
# Warmup Iteration   1: 4.262 ops/ms
Iteration   1: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.267 ops/ms


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
# Warmup Iteration   1: 2.280 ops/ms
Iteration   1: 3.822 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.822 ops/ms


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.052 ms/op
Iteration   1: 3.115 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.115 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.050 ms/op
Iteration   1: 1.958 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.958 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.063 ms/op
Iteration   1: 3.007 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.007 ms/op


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
# Warmup Iteration   1: 12.133 ±(99.9%) 0.295 ms/op
Iteration   1: 8.135 ±(99.9%) 0.065 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.135 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.093 ms/op
Iteration   1: 2.786 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.065 ms/op
                 createUser·p0.99:   8.409 ms/op
                 createUser·p0.999:  13.673 ms/op
                 createUser·p0.9999: 14.991 ms/op
                 createUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11488
  mean =      2.786 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 5694 
    [ 2.500,  3.750) = 4822 
    [ 3.750,  5.000) = 661 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.065 ms/op
     p(99.0000) =      8.409 ms/op
     p(99.9000) =     13.673 ms/op
     p(99.9900) =     14.991 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.096 ms/op
Iteration   1: 1.960 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.405 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   3.570 ms/op
                 existUser·p0.999:  19.846 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16339
  mean =      1.960 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15093 
    [ 2.500,  5.000) = 1176 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.405 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.570 ms/op
     p(99.9000) =     19.846 ms/op
     p(99.9900) =     20.677 ms/op
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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.096 ms/op
Iteration   1: 3.033 ±(99.9%) 0.102 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.843 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.821 ms/op
                 getUser·p0.999:  59.834 ms/op
                 getUser·p0.9999: 60.665 ms/op
                 getUser·p1.00:   60.686 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10548
  mean =      3.033 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10471 
    [ 5.000, 10.000) = 45 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 25 
    [60.000, 65.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.821 ms/op
     p(99.9000) =     59.834 ms/op
     p(99.9900) =     60.665 ms/op
     p(99.9990) =     60.686 ms/op
     p(99.9999) =     60.686 ms/op
    p(100.0000) =     60.686 ms/op


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
# Warmup Iteration   1: 12.116 ±(99.9%) 0.411 ms/op
Iteration   1: 8.274 ±(99.9%) 0.338 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   7.332 ms/op
                 listUser·p0.90:   10.453 ms/op
                 listUser·p0.95:   12.157 ms/op
                 listUser·p0.99:   20.818 ms/op
                 listUser·p0.999:  74.801 ms/op
                 listUser·p0.9999: 79.036 ms/op
                 listUser·p1.00:   79.036 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3827
  mean =      8.274 ±(99.9%) 0.338 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 174 
    [ 5.000, 10.000) = 3196 
    [10.000, 15.000) = 364 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 9 
    [70.000, 75.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      3.060 ms/op
     p(50.0000) =      7.332 ms/op
     p(90.0000) =     10.453 ms/op
     p(95.0000) =     12.157 ms/op
     p(99.0000) =     20.818 ms/op
     p(99.9000) =     74.801 ms/op
     p(99.9900) =     79.036 ms/op
     p(99.9990) =     79.036 ms/op
     p(99.9999) =     79.036 ms/op
    p(100.0000) =     79.036 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.973          ops/ms
Client.existUser                       thrpt         12.894          ops/ms
Client.getUser                         thrpt          8.267          ops/ms
Client.listUser                        thrpt          3.822          ops/ms
Client.createUser                       avgt          3.115           ms/op
Client.existUser                        avgt          1.958           ms/op
Client.getUser                          avgt          3.007           ms/op
Client.listUser                         avgt          8.135           ms/op
Client.createUser                     sample  11488   2.786 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.931           ms/op
Client.createUser:createUser·p0.50    sample          2.503           ms/op
Client.createUser:createUser·p0.90    sample          3.584           ms/op
Client.createUser:createUser·p0.95    sample          4.065           ms/op
Client.createUser:createUser·p0.99    sample          8.409           ms/op
Client.createUser:createUser·p0.999   sample         13.673           ms/op
Client.createUser:createUser·p0.9999  sample         14.991           ms/op
Client.createUser:createUser·p1.00    sample         14.991           ms/op
Client.existUser                      sample  16339   1.960 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.405           ms/op
Client.existUser:existUser·p0.50      sample          1.802           ms/op
Client.existUser:existUser·p0.90      sample          2.396           ms/op
Client.existUser:existUser·p0.95      sample          2.683           ms/op
Client.existUser:existUser·p0.99      sample          3.570           ms/op
Client.existUser:existUser·p0.999     sample         19.846           ms/op
Client.existUser:existUser·p0.9999    sample         20.677           ms/op
Client.existUser:existUser·p1.00      sample         20.677           ms/op
Client.getUser                        sample  10548   3.033 ± 0.102   ms/op
Client.getUser:getUser·p0.00          sample          0.645           ms/op
Client.getUser:getUser·p0.50          sample          2.843           ms/op
Client.getUser:getUser·p0.90          sample          3.748           ms/op
Client.getUser:getUser·p0.95          sample          3.990           ms/op
Client.getUser:getUser·p0.99          sample          4.821           ms/op
Client.getUser:getUser·p0.999         sample         59.834           ms/op
Client.getUser:getUser·p0.9999        sample         60.665           ms/op
Client.getUser:getUser·p1.00          sample         60.686           ms/op
Client.listUser                       sample   3827   8.274 ± 0.338   ms/op
Client.listUser:listUser·p0.00        sample          3.060           ms/op
Client.listUser:listUser·p0.50        sample          7.332           ms/op
Client.listUser:listUser·p0.90        sample         10.453           ms/op
Client.listUser:listUser·p0.95        sample         12.157           ms/op
Client.listUser:listUser·p0.99        sample         20.818           ms/op
Client.listUser:listUser·p0.999       sample         74.801           ms/op
Client.listUser:listUser·p0.9999      sample         79.036           ms/op
Client.listUser:listUser·p1.00        sample         79.036           ms/op
