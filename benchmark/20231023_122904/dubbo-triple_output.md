# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.037 ops/ms
# Warmup Iteration   2: 2.219 ops/ms
# Warmup Iteration   3: 5.054 ops/ms
Iteration   1: 5.478 ops/ms
Iteration   2: 5.586 ops/ms
Iteration   3: 5.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.597 ±(99.9%) 2.263 ops/ms [Average]
  (min, avg, max) = (5.478, 5.597, 5.725), stdev = 0.124
  CI (99.9%): [3.334, 7.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 4.716 ops/ms
# Warmup Iteration   3: 5.618 ops/ms
Iteration   1: 5.908 ops/ms
Iteration   2: 5.955 ops/ms
Iteration   3: 5.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.911 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (5.870, 5.911, 5.955), stdev = 0.043
  CI (99.9%): [5.133, 6.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 4.234 ops/ms
# Warmup Iteration   3: 5.252 ops/ms
Iteration   1: 5.050 ops/ms
Iteration   2: 5.666 ops/ms
Iteration   3: 5.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.418 ±(99.9%) 5.927 ops/ms [Average]
  (min, avg, max) = (5.050, 5.418, 5.666), stdev = 0.325
  CI (99.9%): [≈ 0, 11.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.497 ops/ms
# Warmup Iteration   2: 3.482 ops/ms
# Warmup Iteration   3: 4.722 ops/ms
Iteration   1: 4.810 ops/ms
Iteration   2: 4.810 ops/ms
Iteration   3: 4.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.792 ±(99.9%) 0.558 ops/ms [Average]
  (min, avg, max) = (4.757, 4.792, 4.810), stdev = 0.031
  CI (99.9%): [4.235, 5.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 20.693 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.684 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.874 ±(99.9%) 0.020 ms/op
Iteration   1: 5.939 ±(99.9%) 0.013 ms/op
Iteration   2: 5.624 ±(99.9%) 0.025 ms/op
Iteration   3: 5.714 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.759 ±(99.9%) 2.955 ms/op [Average]
  (min, avg, max) = (5.624, 5.759, 5.939), stdev = 0.162
  CI (99.9%): [2.804, 8.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.378 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.418 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.547 ±(99.9%) 0.008 ms/op
Iteration   1: 5.406 ±(99.9%) 0.006 ms/op
Iteration   2: 5.447 ±(99.9%) 0.007 ms/op
Iteration   3: 5.323 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.392 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (5.323, 5.392, 5.447), stdev = 0.064
  CI (99.9%): [4.232, 6.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.105 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 7.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.839 ±(99.9%) 0.007 ms/op
Iteration   1: 5.614 ±(99.9%) 0.007 ms/op
Iteration   2: 5.892 ±(99.9%) 0.006 ms/op
Iteration   3: 5.522 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.676 ±(99.9%) 3.514 ms/op [Average]
  (min, avg, max) = (5.522, 5.676, 5.892), stdev = 0.193
  CI (99.9%): [2.163, 9.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.103 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.659 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.434 ±(99.9%) 0.016 ms/op
Iteration   1: 6.509 ±(99.9%) 0.013 ms/op
Iteration   2: 6.512 ±(99.9%) 0.014 ms/op
Iteration   3: 6.424 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.482 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (6.424, 6.482, 6.512), stdev = 0.050
  CI (99.9%): [5.571, 7.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.536 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.049 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.231 ±(99.9%) 0.033 ms/op
Iteration   1: 5.800 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   11.780 ms/op
                 createUser·p0.999:  25.657 ms/op
                 createUser·p0.9999: 52.264 ms/op
                 createUser·p1.00:   59.048 ms/op

Iteration   2: 5.443 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.545 ms/op
                 createUser·p0.95:   7.471 ms/op
                 createUser·p0.99:   10.895 ms/op
                 createUser·p0.999:  26.149 ms/op
                 createUser·p0.9999: 40.108 ms/op
                 createUser·p1.00:   41.091 ms/op

Iteration   3: 5.592 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.876 ms/op
                 createUser·p0.999:  29.470 ms/op
                 createUser·p0.9999: 34.181 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171062
  mean =      5.608 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53474 
    [ 5.000, 10.000) = 114755 
    [10.000, 15.000) = 2452 
    [15.000, 20.000) = 145 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 92 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.879 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     25.887 ms/op
     p(99.9900) =     51.905 ms/op
     p(99.9990) =     57.930 ms/op
     p(99.9999) =     59.048 ms/op
    p(100.0000) =     59.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 16.287 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.083 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.520 ±(99.9%) 0.023 ms/op
Iteration   1: 5.435 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.709 ms/op
                 existUser·p0.95:   7.954 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  21.923 ms/op
                 existUser·p0.9999: 25.445 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 5.336 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.482 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.879 ms/op
                 existUser·p0.999:  22.127 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 5.222 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.466 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  17.065 ms/op
                 existUser·p0.9999: 29.312 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179944
  mean =      5.330 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 87329 
    [ 5.000,  7.500) = 83174 
    [ 7.500, 10.000) = 7189 
    [10.000, 12.500) = 1255 
    [12.500, 15.000) = 505 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     21.465 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     34.420 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.518 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.740 ±(99.9%) 0.022 ms/op
Iteration   1: 5.998 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.034 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.381 ms/op
                 getUser·p0.95:   9.634 ms/op
                 getUser·p0.99:   13.992 ms/op
                 getUser·p0.999:  23.921 ms/op
                 getUser·p0.9999: 29.032 ms/op
                 getUser·p1.00:   31.523 ms/op

Iteration   2: 5.903 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   9.929 ms/op
                 getUser·p0.99:   14.844 ms/op
                 getUser·p0.999:  25.795 ms/op
                 getUser·p0.9999: 28.917 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 5.599 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   10.798 ms/op
                 getUser·p0.999:  26.398 ms/op
                 getUser·p0.9999: 29.763 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164745
  mean =      5.828 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 43660 
    [ 5.000,  7.500) = 107377 
    [ 7.500, 10.000) = 7916 
    [10.000, 12.500) = 3470 
    [12.500, 15.000) = 1314 
    [15.000, 17.500) = 583 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     24.814 ms/op
     p(99.9900) =     29.231 ms/op
     p(99.9990) =     31.353 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.352 ±(99.9%) 0.364 ms/op
# Warmup Iteration   2: 7.776 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.604 ±(99.9%) 0.023 ms/op
Iteration   1: 6.635 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.486 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.648 ms/op
                 listUser·p0.999:  27.427 ms/op
                 listUser·p0.9999: 29.208 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 6.541 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  30.888 ms/op
                 listUser·p0.9999: 37.232 ms/op
                 listUser·p1.00:   39.256 ms/op

Iteration   3: 6.456 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  27.109 ms/op
                 listUser·p0.9999: 34.039 ms/op
                 listUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146689
  mean =      6.543 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 5978 
    [ 5.000,  7.500) = 120684 
    [ 7.500, 10.000) = 14469 
    [10.000, 12.500) = 3633 
    [12.500, 15.000) = 1212 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      7.938 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     13.124 ms/op
     p(99.9000) =     28.168 ms/op
     p(99.9900) =     36.394 ms/op
     p(99.9990) =     38.399 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.597 ± 2.263  ops/ms
ClientPb.existUser                       thrpt       3   5.911 ± 0.779  ops/ms
ClientPb.getUser                         thrpt       3   5.418 ± 5.927  ops/ms
ClientPb.listUser                        thrpt       3   4.792 ± 0.558  ops/ms
ClientPb.createUser                       avgt       3   5.759 ± 2.955   ms/op
ClientPb.existUser                        avgt       3   5.392 ± 1.160   ms/op
ClientPb.getUser                          avgt       3   5.676 ± 3.514   ms/op
ClientPb.listUser                         avgt       3   6.482 ± 0.910   ms/op
ClientPb.createUser                     sample  171062   5.608 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.395           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.879           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.223           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.887           ms/op
ClientPb.createUser:createUser·p0.9999  sample          51.905           ms/op
ClientPb.createUser:createUser·p1.00    sample          59.048           ms/op
ClientPb.existUser                      sample  179944   5.330 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.022           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.594           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.465           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.329           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  164745   5.828 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.872           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.913           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.533           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.814           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.231           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  146689   6.543 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.486           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.168           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.394           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.256           ms/op
