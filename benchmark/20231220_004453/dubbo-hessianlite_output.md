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
# Warmup Iteration   1: 2.588 ops/ms
Iteration   1: 5.652 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.652 ops/ms


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
# Warmup Iteration   1: 5.636 ops/ms
Iteration   1: 16.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  16.377 ops/ms


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
# Warmup Iteration   1: 3.901 ops/ms
Iteration   1: 7.479 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.479 ops/ms


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
# Warmup Iteration   1: 2.045 ops/ms
Iteration   1: 3.285 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.285 ops/ms


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
# Warmup Iteration   1: 5.283 ±(99.9%) 0.066 ms/op
Iteration   1: 2.904 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.904 ms/op


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
# Warmup Iteration   1: 2.930 ±(99.9%) 0.032 ms/op
Iteration   1: 1.801 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.801 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.063 ms/op
Iteration   1: 3.053 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.053 ms/op


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
# Warmup Iteration   1: 13.211 ±(99.9%) 0.224 ms/op
Iteration   1: 8.760 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.760 ms/op


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
# Warmup Iteration   1: 4.940 ±(99.9%) 0.089 ms/op
Iteration   1: 2.993 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   2.834 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   6.551 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 11.239 ms/op
                 createUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10683
  mean =      2.993 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 102 
    [ 2.000,  3.000) = 6700 
    [ 3.000,  4.000) = 3475 
    [ 4.000,  5.000) = 199 
    [ 5.000,  6.000) = 92 
    [ 6.000,  7.000) = 20 
    [ 7.000,  8.000) = 39 
    [ 8.000,  9.000) = 23 
    [ 9.000, 10.000) = 1 
    [10.000, 11.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      6.551 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     11.239 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.073 ms/op
Iteration   1: 1.956 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   1.855 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.687 ms/op
                 existUser·p0.999:  32.122 ms/op
                 existUser·p0.9999: 32.893 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16343
  mean =      1.956 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15091 
    [ 2.500,  5.000) = 1179 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.687 ms/op
     p(99.9000) =     32.122 ms/op
     p(99.9900) =     32.893 ms/op
     p(99.9990) =     32.997 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.098 ms/op
Iteration   1: 3.478 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  8.297 ms/op
                 getUser·p0.9999: 10.174 ms/op
                 getUser·p1.00:   10.174 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9198
  mean =      3.478 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 162 
    [ 2.000,  3.000) = 2151 
    [ 3.000,  4.000) = 5101 
    [ 4.000,  5.000) = 1487 
    [ 5.000,  6.000) = 153 
    [ 6.000,  7.000) = 107 
    [ 7.000,  8.000) = 26 
    [ 8.000,  9.000) = 10 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =      8.297 ms/op
     p(99.9900) =     10.174 ms/op
     p(99.9990) =     10.174 ms/op
     p(99.9999) =     10.174 ms/op
    p(100.0000) =     10.174 ms/op


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
# Warmup Iteration   1: 13.760 ±(99.9%) 0.541 ms/op
Iteration   1: 7.854 ±(99.9%) 0.107 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   7.553 ms/op
                 listUser·p0.90:   10.224 ms/op
                 listUser·p0.95:   11.469 ms/op
                 listUser·p0.99:   14.706 ms/op
                 listUser·p0.999:  19.885 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4071
  mean =      7.854 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 148 
    [ 5.000,  7.500) = 1822 
    [ 7.500, 10.000) = 1646 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      7.553 ms/op
     p(90.0000) =     10.224 ms/op
     p(95.0000) =     11.469 ms/op
     p(99.0000) =     14.706 ms/op
     p(99.9000) =     19.885 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.652          ops/ms
Client.existUser                       thrpt         16.377          ops/ms
Client.getUser                         thrpt          7.479          ops/ms
Client.listUser                        thrpt          3.285          ops/ms
Client.createUser                       avgt          2.904           ms/op
Client.existUser                        avgt          1.801           ms/op
Client.getUser                          avgt          3.053           ms/op
Client.listUser                         avgt          8.760           ms/op
Client.createUser                     sample  10683   2.993 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.243           ms/op
Client.createUser:createUser·p0.50    sample          2.834           ms/op
Client.createUser:createUser·p0.90    sample          3.617           ms/op
Client.createUser:createUser·p0.95    sample          3.887           ms/op
Client.createUser:createUser·p0.99    sample          6.551           ms/op
Client.createUser:createUser·p0.999   sample         11.158           ms/op
Client.createUser:createUser·p0.9999  sample         11.239           ms/op
Client.createUser:createUser·p1.00    sample         11.239           ms/op
Client.existUser                      sample  16343   1.956 ± 0.036   ms/op
Client.existUser:existUser·p0.00      sample          0.642           ms/op
Client.existUser:existUser·p0.50      sample          1.855           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.601           ms/op
Client.existUser:existUser·p0.99      sample          3.687           ms/op
Client.existUser:existUser·p0.999     sample         32.122           ms/op
Client.existUser:existUser·p0.9999    sample         32.893           ms/op
Client.existUser:existUser·p1.00      sample         32.997           ms/op
Client.getUser                        sample   9198   3.478 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.362           ms/op
Client.getUser:getUser·p0.50          sample          3.445           ms/op
Client.getUser:getUser·p0.90          sample          4.284           ms/op
Client.getUser:getUser·p0.95          sample          4.686           ms/op
Client.getUser:getUser·p0.99          sample          6.406           ms/op
Client.getUser:getUser·p0.999         sample          8.297           ms/op
Client.getUser:getUser·p0.9999        sample         10.174           ms/op
Client.getUser:getUser·p1.00          sample         10.174           ms/op
Client.listUser                       sample   4071   7.854 ± 0.107   ms/op
Client.listUser:listUser·p0.00        sample          1.364           ms/op
Client.listUser:listUser·p0.50        sample          7.553           ms/op
Client.listUser:listUser·p0.90        sample         10.224           ms/op
Client.listUser:listUser·p0.95        sample         11.469           ms/op
Client.listUser:listUser·p0.99        sample         14.706           ms/op
Client.listUser:listUser·p0.999       sample         19.885           ms/op
Client.listUser:listUser·p0.9999      sample         23.036           ms/op
Client.listUser:listUser·p1.00        sample         23.036           ms/op
