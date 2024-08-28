# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.895 ops/ms
Iteration   1: 7.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.534 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.810 ops/ms
Iteration   1: 13.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.211 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.322 ops/ms
Iteration   1: 13.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.205 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.341 ops/ms
Iteration   1: 8.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.714 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.153 ±(99.9%) 0.076 ms/op
Iteration   1: 2.441 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.441 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ±(99.9%) 0.092 ms/op
Iteration   1: 2.071 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ±(99.9%) 0.069 ms/op
Iteration   1: 2.239 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.239 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ±(99.9%) 0.093 ms/op
Iteration   1: 3.121 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.118 ms/op
Iteration   1: 2.201 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.872 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   4.562 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 18.706 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14607
  mean =      2.201 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 11117 
    [ 2.500,  3.750) = 2890 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.872 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      4.562 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     18.706 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.057 ±(99.9%) 0.073 ms/op
Iteration   1: 2.004 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   3.194 ms/op
                 existUser·p0.999:  15.958 ms/op
                 existUser·p0.9999: 24.976 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15956
  mean =      2.004 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14328 
    [ 2.500,  5.000) = 1562 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.194 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     24.976 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.302 ms/op
Iteration   1: 2.280 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   2.236 ms/op
                 getUser·p0.90:   2.896 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14022
  mean =      2.280 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 9736 
    [ 2.500,  3.750) = 3895 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ±(99.9%) 0.139 ms/op
Iteration   1: 3.194 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  11.419 ms/op
                 listUser·p0.9999: 11.452 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10039
  mean =      3.194 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1029 
    [ 2.500,  3.750) = 6940 
    [ 3.750,  5.000) = 1900 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.419 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     11.452 ms/op
     p(99.9999) =     11.452 ms/op
    p(100.0000) =     11.452 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.534          ops/ms
ClientSimple.existUser                       thrpt         13.211          ops/ms
ClientSimple.getUser                         thrpt         13.205          ops/ms
ClientSimple.listUser                        thrpt          8.714          ops/ms
ClientSimple.createUser                       avgt          2.441           ms/op
ClientSimple.existUser                        avgt          2.071           ms/op
ClientSimple.getUser                          avgt          2.239           ms/op
ClientSimple.listUser                         avgt          3.121           ms/op
ClientSimple.createUser                     sample  14607   2.201 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.728           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.872           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.562           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.990           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.706           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.842           ms/op
ClientSimple.existUser                      sample  15956   2.004 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.568           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.954           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.194           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.958           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.976           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.035           ms/op
ClientSimple.getUser                        sample  14022   2.280 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.591           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.236           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.879           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.334           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.662           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.662           ms/op
ClientSimple.listUser                       sample  10039   3.194 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.194           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.908           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.808           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.419           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.452           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.452           ms/op

Benchmark result is saved to 1724805868945.json
