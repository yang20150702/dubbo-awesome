# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.386 ops/ms
Iteration   1: 3.642 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.642 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.908 ops/ms
Iteration   1: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.789 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.651 ops/ms
Iteration   1: 4.473 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.473 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.079 ops/ms
Iteration   1: 1.505 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.505 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.025 ±(99.9%) 0.218 ms/op
Iteration   1: 4.881 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.881 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.549 ±(99.9%) 0.102 ms/op
Iteration   1: 2.430 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.430 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.151 ±(99.9%) 0.549 ms/op
Iteration   1: 4.775 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.775 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 25.692 ±(99.9%) 0.870 ms/op
Iteration   1: 18.330 ±(99.9%) 0.191 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.330 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.188 ±(99.9%) 0.282 ms/op
Iteration   1: 3.341 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   2.843 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   11.700 ms/op
                 createUser·p0.999:  24.543 ms/op
                 createUser·p0.9999: 25.199 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9587
  mean =      3.341 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 187 
    [ 2.500,  5.000) = 8757 
    [ 5.000,  7.500) = 349 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =     11.700 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.108 ±(99.9%) 0.174 ms/op
Iteration   1: 2.062 ±(99.9%) 0.045 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   4.435 ms/op
                 existUser·p0.99:   9.522 ms/op
                 existUser·p0.999:  24.773 ms/op
                 existUser·p0.9999: 24.951 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15545
  mean =      2.062 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13879 
    [ 2.500,  5.000) = 1067 
    [ 5.000,  7.500) = 195 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      4.435 ms/op
     p(99.0000) =      9.522 ms/op
     p(99.9000) =     24.773 ms/op
     p(99.9900) =     24.951 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 10.183 ±(99.9%) 0.328 ms/op
Iteration   1: 4.100 ±(99.9%) 0.088 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   6.714 ms/op
                 getUser·p0.95:   9.062 ms/op
                 getUser·p0.99:   13.230 ms/op
                 getUser·p0.999:  20.611 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7793
  mean =      4.100 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 636 
    [ 2.500,  5.000) = 5841 
    [ 5.000,  7.500) = 693 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      6.714 ms/op
     p(95.0000) =      9.062 ms/op
     p(99.0000) =     13.230 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 24.615 ±(99.9%) 0.700 ms/op
Iteration   1: 15.798 ±(99.9%) 0.459 ms/op
                 listUser·p0.00:   4.067 ms/op
                 listUser·p0.50:   14.762 ms/op
                 listUser·p0.90:   22.839 ms/op
                 listUser·p0.95:   25.258 ms/op
                 listUser·p0.99:   40.326 ms/op
                 listUser·p0.999:  55.113 ms/op
                 listUser·p0.9999: 55.837 ms/op
                 listUser·p1.00:   55.837 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2041
  mean =     15.798 ±(99.9%) 0.459 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10 
    [ 5.000, 10.000) = 247 
    [10.000, 15.000) = 798 
    [15.000, 20.000) = 606 
    [20.000, 25.000) = 267 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 10 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      4.067 ms/op
     p(50.0000) =     14.762 ms/op
     p(90.0000) =     22.839 ms/op
     p(95.0000) =     25.258 ms/op
     p(99.0000) =     40.326 ms/op
     p(99.9000) =     55.113 ms/op
     p(99.9900) =     55.837 ms/op
     p(99.9990) =     55.837 ms/op
     p(99.9999) =     55.837 ms/op
    p(100.0000) =     55.837 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.642          ops/ms
Client.existUser                       thrpt         10.789          ops/ms
Client.getUser                         thrpt          4.473          ops/ms
Client.listUser                        thrpt          1.505          ops/ms
Client.createUser                       avgt          4.881           ms/op
Client.existUser                        avgt          2.430           ms/op
Client.getUser                          avgt          4.775           ms/op
Client.listUser                         avgt         18.330           ms/op
Client.createUser                     sample   9587   3.341 ± 0.060   ms/op
Client.createUser:createUser·p0.00    sample          1.686           ms/op
Client.createUser:createUser·p0.50    sample          2.843           ms/op
Client.createUser:createUser·p0.90    sample          4.178           ms/op
Client.createUser:createUser·p0.95    sample          5.652           ms/op
Client.createUser:createUser·p0.99    sample         11.700           ms/op
Client.createUser:createUser·p0.999   sample         24.543           ms/op
Client.createUser:createUser·p0.9999  sample         25.199           ms/op
Client.createUser:createUser·p1.00    sample         25.199           ms/op
Client.existUser                      sample  15545   2.062 ± 0.045   ms/op
Client.existUser:existUser·p0.00      sample          0.500           ms/op
Client.existUser:existUser·p0.50      sample          1.669           ms/op
Client.existUser:existUser·p0.90      sample          2.601           ms/op
Client.existUser:existUser·p0.95      sample          4.435           ms/op
Client.existUser:existUser·p0.99      sample          9.522           ms/op
Client.existUser:existUser·p0.999     sample         24.773           ms/op
Client.existUser:existUser·p0.9999    sample         24.951           ms/op
Client.existUser:existUser·p1.00      sample         24.969           ms/op
Client.getUser                        sample   7793   4.100 ± 0.088   ms/op
Client.getUser:getUser·p0.00          sample          0.955           ms/op
Client.getUser:getUser·p0.50          sample          3.293           ms/op
Client.getUser:getUser·p0.90          sample          6.714           ms/op
Client.getUser:getUser·p0.95          sample          9.062           ms/op
Client.getUser:getUser·p0.99          sample         13.230           ms/op
Client.getUser:getUser·p0.999         sample         20.611           ms/op
Client.getUser:getUser·p0.9999        sample         21.529           ms/op
Client.getUser:getUser·p1.00          sample         21.529           ms/op
Client.listUser                       sample   2041  15.798 ± 0.459   ms/op
Client.listUser:listUser·p0.00        sample          4.067           ms/op
Client.listUser:listUser·p0.50        sample         14.762           ms/op
Client.listUser:listUser·p0.90        sample         22.839           ms/op
Client.listUser:listUser·p0.95        sample         25.258           ms/op
Client.listUser:listUser·p0.99        sample         40.326           ms/op
Client.listUser:listUser·p0.999       sample         55.113           ms/op
Client.listUser:listUser·p0.9999      sample         55.837           ms/op
Client.listUser:listUser·p1.00        sample         55.837           ms/op
